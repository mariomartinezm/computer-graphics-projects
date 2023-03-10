cmake_minimum_required(VERSION 3.2)

project(OpenGLProjects LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(Fundamentals/SpecifyingVertexData)
add_subdirectory(Fundamentals/Instancing)
add_subdirectory(Fundamentals/Camera)

add_subdirectory(ComputeShaders/ParticleSystem)
add_subdirectory(ComputeShaders/PrefixSum)
add_subdirectory(ComputeShaders/PSO)
add_subdirectory(ComputeShaders/RayTracing)
add_subdirectory(ComputeShaders/SBFlocking)
add_subdirectory(ComputeShaders/TEAPRNG)
add_subdirectory(ComputeShaders/TextureReadAndWrite)

add_subdirectory(DearImGui/Test)
add_subdirectory(DearImGui/PositionAndColor)
