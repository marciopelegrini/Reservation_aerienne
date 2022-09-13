cmake_minimum_required(VERSION 3.23)
project(Reservation_aerienne C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(inc)

add_executable(Reservation_aerienne
        inc/airline_reservation.h
        src/airline_reservation.c
        project_main.c)
