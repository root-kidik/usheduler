cmake_minimum_required(VERSION 3.12)

include(cmake/Config.cmake)

project(uscheduler LANGUAGES C CXX ASM)

add_subdirectory(drivers)
add_subdirectory(src/${PROJECT_NAME})