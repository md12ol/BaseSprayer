cmake_minimum_required(VERSION 3.16)
project(BaseSprayer)

set(CMAKE_CXX_STANDARD 20)

add_executable(BaseSprayer BaseSprayer/main.cpp
        BaseSprayer/bitspray.h
        BaseSprayer/bitspray.cpp
        BaseSprayer/stat.h
        BaseSprayer/stat.cpp)

set_property(TARGET BaseSprayer PROPERTY WORKING_DIRECTORY ./)