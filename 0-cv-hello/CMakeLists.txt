cmake_minimum_required(VERSION 2.8)

project(saveVideo)

find_package(OpenCV REQUIRED)

include_directories(${OpenCV_INCLUDE_DIRS})

add_executable(saveVideo saveVideo.cpp)

target_link_libraries(saveVideo ${OpenCV_LIBS})
