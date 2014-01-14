cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(hello NONE)

enable_language(Fortran)

add_executable(hello hello.f90)
