cmake_minimum_required(VERSION 3.17)
project(server)

set(CMAKE_C_STANDARD 99)

add_executable(server main.c httpd.c)
