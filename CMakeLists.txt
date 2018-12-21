cmake_minimum_required(VERSION 3.12)
project(RPLSH_CUDA)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(RPLSH_CUDA
        evaluation.cpp
        index.cu
        search.cu
        util.cpp
        util.h)
