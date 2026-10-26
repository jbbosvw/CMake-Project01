cmake_minimum_required(VERSION 3.10)
project(CMakeProject01)

add_executable(CMakeProject01 src/main.c src/hello.c)
target_include_directories(CMakeProject01 PRIVATE include)