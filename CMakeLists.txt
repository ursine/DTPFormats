cmake_minimum_required (VERSION 2.6)

if(UNIX)
    set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -std=gnu++11 -g")
endif()
 

project(make_swatches)
add_executable(make_swatches make_swatches.cpp)
