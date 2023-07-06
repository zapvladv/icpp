cmake_minimum_required(VERSION 3.10)

project(HelloWorld)

add_executable(HelloWorld main.cpp)

install(TARGETS HelloWorld DESTINATION bin)
