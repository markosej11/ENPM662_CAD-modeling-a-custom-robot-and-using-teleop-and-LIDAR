# ENPM662-Project 1 - Markose
Recommended tools:
1) ROS melodic
2)Gazebo 9.14


Follow the following steps to run the package succesfully 
1)Copy and paste the package 'toycar' (Placed inside package directory) into your catkin_ws/src 
2) $ cd catkin_ws
3) $ catkin_make
4) source your workspace
5) To launch the model on Gazebo do, 
	$ roslaunch toycar3 template_launch.launch 
6) To run teleop, from another terminal do.
	$ rosrun toycar3 teleop_template.py 
7) To the output of the lidar on Rviz open a new terminal and do 
	$ rviz
8) now use the keyboard to move the robot in gazebo and have fun!!

Note:
Don't forget to source the terminal eveytime you open a new one. 




