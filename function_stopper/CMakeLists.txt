add_library(fn_stopper
        function_stopper_base.h function_stopper_base.cpp
        time_profiler.h time_profiler.cpp)


add_executable(function_stopper_base_example function_stopper_base_example.cpp
        function_stopper_base.h function_stopper_base.cpp
        )
