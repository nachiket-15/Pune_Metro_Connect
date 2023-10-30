cmake_minimum_required(VERSION 3.0)
project(MyApp)

set(SOURCES
    src/check_station.c
    src/creategraph.c
    src/display_time.c
    src/displayTimeTable.c
    src/DSA_Project_final.c  # Remove redundant .c extension
    src/station_names.c
    src/station_not_found.c
    src/station.c
)

include_directories(include)

add_executable(DSA_Project ${SOURCES})
