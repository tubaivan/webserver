cmake_minimum_required(VERSION 2.6)
project(webserver)

add_executable(webserver main.cpp)

install(TARGETS webserver RUNTIME DESTINATION bin)
