cmake_minimum_required(VERSION 3.13)

project(hello)

set(CMAKE_CXX_STANDARD 17)

file(GLOB SOURCES "src/*")
add_executable(hello ${SOURCES})