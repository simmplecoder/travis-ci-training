project(area51)
cmake_minimum_required(VERSION 3.2)

include(CTest)
enable_testing()

add_executable(app main.cpp)

add_test(app-test app)

