# BloX PCA9685

The BloX PCA9685 implements a ROS driver to communicate with a PCA9685 PWM Signal Generator over I2C. This chip is used for example in the following Adafruit products: 

- [Adafruit 8-Channel PWM or Servo FeatherWing](https://www.adafruit.com/product/2928)
- [Adafruit 16-Channel 12-bit PWM/Servo Shield](https://www.adafruit.com/product/815)
- [Adafruit 16-Channel PWM / Servo HAT for Raspberry Pi](https://www.adafruit.com/product/2327)
- [Adafruit 16-Channel PWM / Servo Bonnet for Raspberry Pi](https://www.adafruit.com/product/3416)

The implementation of the ROS driver relies on [Adafruits ServoKit Library](https://docs.circuitpython.org/projects/servokit/en/latest/index.html)

## Data

The BloX PCA9685 subscribes to command velocities on the topic **/pca9685/cmd** of type [std_msgs/msg/Float32MultiArray](https://docs.ros2.org/galactic/api/std_msgs/msg/Float32MultiArray.html).

