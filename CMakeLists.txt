cmake_minimum_required(VERSION 3.16)

project(bgtuts VERSION 0.1.0)

set (CMAKE_CXX_STANDARD 17)
set (CMAKE_CXX_STANDARD_REQUIRED true)

add_executable(${PROJECT_NAME} src/main.cpp)