cmake_minimum_required(VERSION 3.23)

project(valet)

set(CMAKE_CXX_STANDARD 20)

set (COMPILATION_DIR ${CMAKE_CURRENT_SOURCE_DIR}/src/core)

add_executable(valet
    src/main.cpp
    ${COMPILATION_DIR}/lexer.h
    ${COMPILATION_DIR}/lexer.cpp
)
