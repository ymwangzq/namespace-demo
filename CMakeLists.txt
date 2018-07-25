cmake_minimum_required(VERSION 3.10)
project(namespace_demo)

set(CMAKE_CXX_STANDARD 11)

add_executable(namespace_demo main.cpp)
add_executable(origin_clone demos/origin_clone.cpp)
add_executable(UTS_namespace demos/UTS_namespace.cpp)
