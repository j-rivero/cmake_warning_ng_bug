cmake_minimum_required(VERSION 3.5)
project(warning_ng_bug)

include(ExternalProject)
externalproject_add(testing_external
  PREFIX "external"
  INSTALL_COMMAND ""
  SOURCE_DIR "${CMAKE_CURRENT_SOURCE_DIR}/warning_external"
)
