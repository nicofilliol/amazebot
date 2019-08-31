# AMazeBot
This repository holds all the files that build the Arduino firmware of the robot used during the RobotCraft 2019 
summer programme. It contains code to accomplish the following things:
* Read encoder data for kinematics purposes (i.e. calculating speed and odometry)
* Control motors using a PID controller to drive with desired linear and angular speed
* Read the infrared sensors' analog values and convert them into distances
* Setup a ROS connection and subscribe and publish to several topics such as /cmd_vel, /pose, /front_distance etc.
