cmake_minimum_required(VERSION 2.8.3)
project(gazebo_spaceship)
add_compile_options(-std=c++11)
find_package(catkin REQUIRED COMPONENTS
uuv_gazebo_plugins)
catkin_package()
include_directories()
