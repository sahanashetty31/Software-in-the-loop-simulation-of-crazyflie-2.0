# Software in the loop simulation of crazyflie 2.0

Steps to start the launch file of crazyflie 2.0.
Start with the script that will launch Gazebo. The launch file maybe crazyflie_sim.launch .

$ cd '/home/shetty/catkin_ws/src/crazyflie_ros/crazyflie_2.0/crazyflie_gazebo/launch' 

$ ls

$ roslaunch crazyflie_sim.launch


Next, open the script containing python programs for various tasks:		

$ cd '/catkin_ws/src/crazyflie_ros/crazyflie_2.0/crazyflie_gazebo/scripts'

$ ./run_cfs.sh

After running the above script, gyrobias found must be printed on the screen.

Then,run the python programs for several tasks such as testing the vertical trajectory, helix trajectory, waypoint navigation,etc.

$ cd '/catkin_ws/src/crazyflie_ros/crazyflie_2.0/crazyflie_gazebo/scripts'

$ ls

$ python vertical_trajectory.py




