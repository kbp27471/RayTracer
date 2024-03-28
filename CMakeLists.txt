cmake_minimum_required(VERSION 3.0)
project(RayTracer)

set(CMAKE_CXX_STANDARD 11)

# Add the executable target and specify source files
add_executable(inOneWeekend 
    src/main.cc
    src/vec3.h
    src/color.h
    src/camera.h 
    src/ray.h 
    src/hittable.h 
    src/sphere.h 
    src/hittable_list.h 
    src/rtweekend.h
    src/interval.h
)
