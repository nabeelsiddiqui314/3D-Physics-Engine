cmake_minimum_required(VERSION 3.25)

project(3D-Physics-Engine)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED true)

add_executable(${PROJECT_NAME}
	src/main.cpp
)