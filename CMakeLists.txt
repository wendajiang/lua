cmake_minimum_required(VERSION 3.16)
project(lua)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_C_STANDARD 11)

add_definitions(-D USE_MAXOS)

include_directories(./src/)

#add_executable(lua lua.c lprefix.h lua.h luaconf.h lauxlib.c lualib.h)




