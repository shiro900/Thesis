cmake_minimum_required(VERSION 3.3)
project(Thesis)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp Graph.h Graph.cpp Dijkstra.h Dijkstra.cpp AdjListElement.h AdjListElement.cpp)
add_executable(Thesis ${SOURCE_FILES})