add_library(STB_lib INTERFACE)
#get_target_property(CWDS_INTERFACE_INCLUDE_DIRECTORIES AICxx::cwds INTERFACE_INCLUDE_DIRECTORIES)
target_include_directories(STB_lib
INTERFACE
    ./
)