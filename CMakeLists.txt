cmake_minimum_required(VERSION 3.0)

# set the project name
project(hello-mp-cpp)

# define the source
set(SOURCE hello_multi_platform.cpp)

# add the executable for the current project with the defined source
add_executable(${PROJECT_NAME} ${SOURCE})
