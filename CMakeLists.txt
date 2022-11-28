cmake_minimum_required(VERSION 3.18)
project(
        meine_DB_Anwndung
        LANGUAGES CXX
        DESCRIPTION ""
        HOMEPAGE_URL

)


add_executable(        
                ${PROJECT_NAME} 
                "${CMAKE_CURRENT_SOURCE_DIR}/src/main.cpp" 
)
