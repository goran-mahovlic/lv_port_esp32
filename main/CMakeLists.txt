idf_component_register(SRCS main.c)
FILE(GLOB_RECURSE COMPONENT_SRCS
  ${CMAKE_SOURCE_DIR}/src/ui/*.h
  ${CMAKE_SOURCE_DIR}/src/ui/*.c
  ${CMAKE_SOURCE_DIR}/src/ui/*.cpp
)
