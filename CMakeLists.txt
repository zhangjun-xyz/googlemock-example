cmake_minimum_required (VERSION 2.8)
project (googlemock_example)

set(CMAKE_CXX_FLAGS  "-Wall -Wno-sign-compare -g -std=c++14 -O4")

add_subdirectory(unit_test)
