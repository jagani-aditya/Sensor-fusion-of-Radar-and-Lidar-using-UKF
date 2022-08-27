# Sensor-fusion-of-Radar-and-Lidar-using-UKF
Sensor Fusion (LIDAR + RADAR)

## Project Description
This project presents an efficient sensor fusion system for tracking multiple moving vehicles over Light Detection and Ranging (LiDAR) and Radar in autonomous vehicles.
We track an object using measurements from LiDAR and Radar using measurement models, constant-velocity model, and sensor fusion technique.


<p align="center">
  <img src="/Media/map3.jpg" />
</p>

## Platform
* Ubuntu 18.04 LTS
* ROS Melodic
* Gazebo 
* RViz

## Implementation
 
Navigate to the ROS package in the ```catkin_ws``` folder

```$ catkin_make```

```$ source devel/setup.bash ```

``` roslaunch explore_env turtlebot_gazebo.launch ``` 
