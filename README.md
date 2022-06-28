# Turtlebot3_EKF
This repository is a guided tutorial for sensor fusion on Turtlebot3 on ROS noetic.
This project fuses odometry from encoders with lazor sensor readings to create a filtered path using the Extended Kalman Filter. 

Main project is launched using: 

```roslaunch main main.launch```

To move the robot using the keyboard use: 

```rosrun turtlebot3_teleop turtlebot3_teleop_key```
