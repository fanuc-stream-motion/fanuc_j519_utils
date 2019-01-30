cmake_minimum_required(VERSION 2.8.3)
project(fanuc_j519_utils)

find_package(catkin REQUIRED)

# catkin_python_setup()

catkin_package()

install(PROGRAMS
  scripts/stop_robot_state
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
