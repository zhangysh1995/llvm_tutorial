cmake_minimum_required(VERSION 3.5)
project(llvm_tutorial)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(llvm_tutorial ${SOURCE_FILES})