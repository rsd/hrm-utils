cmake_minimum_required(VERSION 2.8.10)

project(hasm C)

include_directories(${hrm_utils_INCLUDE_DIRS})

add_executable(${PROJECT_NAME} asm.c)
