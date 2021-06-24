add_executable(tiny_dnn_benchmarks benchmarks.cpp)
target_link_libraries(tiny_dnn_benchmarks
        ${project_library_target_name} ${REQUIRED_LIBRARIES} benchmark::benchmark)

#### Clang-tidy check
#include(../cmake/clang-cxx-dev-tools.cmake)
