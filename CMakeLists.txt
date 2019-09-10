cmake_minimum_required(VERSION 3.13)
project(ThreadPool)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_executable(ThreadPool
        example.cpp
        ThreadPool.h)
