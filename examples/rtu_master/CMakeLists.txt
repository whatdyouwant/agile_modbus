cmake_minimum_required(VERSION 3.0)

project(rtu_master)

file(GLOB SRCS *.c)

add_executable(RtuMaster ${SRCS})

target_link_libraries(RtuMaster PRIVATE Threads::Threads)
