project(COREPAL)

include(../clrfeatures.cmake)

include_directories(${COREPAL_SOURCE_DIR}/inc)
include_directories(${COREPAL_SOURCE_DIR}/src)
include_directories(${COREPAL_SOURCE_DIR}/../inc)

add_compile_options(-fexceptions)

add_subdirectory(src)
