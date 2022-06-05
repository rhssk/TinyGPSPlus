add_library(TinyGPS INTERFACE)
target_include_directories(TinyGPS INTERFACE src)

zephyr_library()
zephyr_library_sources(src/TinyGPS++.cpp)
zephyr_library_link_libraries(TinyGPS)
