cmake_minimum_required(VERSION 2.8.12)
project(cmake_wrapper)

message(STATUS "Conan CMake Wrapper")
include("conanbuildinfo.cmake")
conan_basic_setup(TARGETS)

add_subdirectory(source_subfolder/cmake)
