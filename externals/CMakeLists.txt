cmake_minimum_required (VERSION 3.17)

set(EXTERNAL_DIR "${CMAKE_CURRENT_SOURCE_DIR}")

include(ExternalProject)

# Project Dependencies:
if(BUILD_TEST)
  set(GTEST_VERSION 1.10.0)
  include(gtest.cmake)
endif()
