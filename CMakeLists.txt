cmake_minimum_required(VERSION 3.8)
project(httpclient)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        http.c
        http.h
        http_parser.c
        http_parser.h
        krypton.c
        krypton.h
        main.c)

add_executable(httpclient ${SOURCE_FILES})