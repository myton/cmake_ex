include_directories(/usr/include/hello)
SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
add_executable(main main.c)
target_link_libraries(main libhello.so)
