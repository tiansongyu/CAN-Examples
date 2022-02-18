cmake_minimum_required(VERSION 3.7)
project(can_example)


add_executable(cantransmit cantransmit.c)
add_executable(canreceive canreceive.c)
add_executable(canfilter canfilter.c)