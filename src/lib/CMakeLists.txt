# Create a library called "sqlite_data_logger_zynq"
add_library(sqlite_data_logger_zynq_lib sqlite_data_logger_zynq.cpp)

# Specify include directories for the library
target_include_directories(sqlite_data_logger_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
