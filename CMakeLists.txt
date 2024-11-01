cmake_minimum_required(VERSION 3.28.3)
project(littlefs C)

add_library(littlefs
    lfs.c
    lfs_util.c
)

target_include_directories(littlefs
    PUBLIC
        "${CMAKE_CURRENT_SOURCE_DIR}"
)