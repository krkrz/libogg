cmake_minimum_required(VERSION 3.4.1)

include_directories( . include )

add_library( ogg STATIC
src/bitwise.c
src/framing.c )

