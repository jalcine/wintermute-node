cmake_minimum_required(VERSION 2.8)

project(WintermuteNode)

include_directories(${CMAKE_JS_INC})

set(_src
  library.cc)

set_target_properties(wintermute PROPERTIES PREFIX "" SUFFIX ".node")
