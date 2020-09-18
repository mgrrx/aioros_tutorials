cmake_minimum_required(VERSION 2.8.3)
project(aioros_tutorials)

find_package(catkin REQUIRED)
catkin_package()

install(
    PROGRAMS
     scripts/listener
     scripts/talker
     scripts/listener_talker
    DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
