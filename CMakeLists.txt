# The following lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.16)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(ESP32S3-Template)

add_compile_options (-DCMAKE_CXX_COMPILER_LAUNCHER=ccache)
set(CMAKE_BUILD_PARALLEL_LEVEL 12)