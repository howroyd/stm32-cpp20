target_sources(StmLib PRIVATE
    "${CMAKE_CURRENT_SOURCE_DIR}/startup_stm32h743xx.s"
)
target_include_directories(StmLib PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")