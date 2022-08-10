cmake_minimum_required(VERSION 3.0.0)

# set the project name
project(cmakeproj VERSION 1.0)

# add the executable
add_executable(cmakeproj cmakeproj.cpp)

# install (please be aware that changing the target folder may lead to issues during deployment and debugging)
install(TARGETS cmakeproj DESTINATION bin)
