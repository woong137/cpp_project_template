cmake_minimum_required(VERSION 3.10) #cmake 최소 버전

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON) #c++17 표준 사용
set(CMAKE_CXX_EXTENSIONS OFF) #추가적인 컴파일러 확장기능 사용 금지

set(CMAKE_VERBOSE_MAKEFILE ON)

project(
    CPP_PROJECT_TEMPLATE
    LANGUAGES CXX
    VERSION 1.0.0
    DESCRIPTION "C++ Project Template"
    
) #프로젝트 이름