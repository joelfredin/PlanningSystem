cmake_minimum_required(VERSION 3.10)
project(MyProject)

add_subdirectory(subproject)

add_executable(MyProject main.cpp)

# target_link_libraries(MyProject subproject)