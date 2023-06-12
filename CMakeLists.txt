cmake_minimum_required(VERSION 3.21)
project(CMakeTestProject
    VERSION 1.0.0.0
    DESCRIPTION "A test project of CMake"
    HOMEPAGE_URL https://github.com/rensilin/cmake-test
    LANGUAGES CXX CUDA)
add_executable(test test.cpp)