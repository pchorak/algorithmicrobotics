cmake_minimum_required(VERSION 2.8.3)
project(pi_camera
)

find_package(catkin REQUIRED COMPONENTS
  rospy
  sensor_msgs
  duckietown_msgs
)

catkin_package()

include_directories(${catkin_INCLUDE_DIRS})
