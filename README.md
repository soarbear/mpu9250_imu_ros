# mpu9250_imu_ros

Arduino code(mpu9250_imu_driver/firmaware) employing rosserial to retrieve a quaternion from the mpu6050 DMP. 

Then, another ROS node(mpu6050_imu_converter) publishing IMU & Pose messages to ROS. 

The package is tested on Arduino Uno compatible & Asus Tinker board(Raspiberry Pi or PC maybe OK).

# Demo

$roslaunch mpu9250_imu_driver mpu9250_imu.launch

video on youtube -> https://youtu.be/ziUGnZDbtfc

# Explanation
<a href="https://memo.soarcloud.com/9%e8%bb%b8imu-mpu-9250%e3%82%92%e3%83%ad%e3%83%9c%e3%83%83%e3%83%88%e3%81%ab%e7%b5%84%e3%81%bf%e8%be%bc%e3%82%82%e3%81%86/">Also explained in Japanese</a>

# Reference
<a href="https://github.com/jrowberg/i2cdevlib">jrowberg/i2cdevlib</a>
