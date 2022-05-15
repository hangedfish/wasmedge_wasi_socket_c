cmake_minimum_required(VERSION 3.16)

project(wasmedge_wasi_socket_c)

add_library(
    wasmedge_wasi_socket_c
    STATIC
    wasi_socket_ext.c
)