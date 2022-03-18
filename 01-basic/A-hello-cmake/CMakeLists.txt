# Set the minimum version of CMake that can be used
# To find the cmake version run
# $ cmake --version
cmake_minimum_required(VERSION 3.5)

# Set the project name
project (hello_cmake)

if(NOT SKIP_TESTS)
    message(STATUS "added tests")
endif()

# Add an executable
add_executable(hello_cmake main.cpp)
