cmake_minimum_required(VERSION 4.0)
project(GTR)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(vendor)

add_subdirectory(src)