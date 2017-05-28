cmake_minimum_required(VERSION 3.7)
project(untitled)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 ")
set(CMAKE_CXX_STANDARD 11)
set (CMAKE_SHARED_LINKER_FLAGS "-lGL -lGLU -lglut")



set(SOURCE_FILES main.cpp)
add_executable(untitled ${SOURCE_FILES})