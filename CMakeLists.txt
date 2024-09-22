CMAKE_MINIMUM_REQUIRED(VERSION 3.10)

project(SortMake)
aux_source_directory(src SRC_SUB)
aux_source_directory(. SRC_CUR)
add_executable(sort ${SRC_SUB} ${SRC_CUR})
include_directories(include)