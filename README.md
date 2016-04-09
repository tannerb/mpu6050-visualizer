# mpu6050-visualizer
Python Processing sketch that draws a sphere and picks points on it via quaternion rotation from a MPU6050 gyroscope.

Works with an MPU6050 and Arduino to send/receive values over serial.

The Arduino should pull quarternion values from the MPU6050 DMP and send them encoded as
`quat <tab> x <tab> y <tab> z <tab> w`


#Initialization

The order of operations to start the system:

Start Arduino
Start Processing

Arduino sends 'start'
