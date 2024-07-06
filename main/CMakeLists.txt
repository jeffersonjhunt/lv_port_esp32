FILE(GLOB_RECURSE demo_sources *.c)

idf_component_register(
        SRCS ${drv_sources}
        INCLUDE_DIRS .
        REQUIRES driver esp_timer
)