cmake_minimum_required(VERSION 3.31.6)
project(jah)

set(CMAKE_CXX_STANDARD 26)

add_executable(jah main.cpp)

install(TARGETS jah DESTINATION bin)

