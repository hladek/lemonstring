cmake_minimum_required(VERSION 2.6)
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../include)
set(SOURCES
Tokenizer.cpp
floatparsef.cpp
utf8proc.c
Command.cpp
UTokenizer.cpp
)

add_library(lemonstring ${SOURCES})
install(TARGETS lemonstring DESTINATION lib)

