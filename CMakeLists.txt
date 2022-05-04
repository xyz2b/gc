cmake_minimum_required(VERSION 3.19)
project(gc)

set(CMAKE_CXX_STANDARD 11)

add_executable(gc main.cpp share/Object.cpp share/Object.h)