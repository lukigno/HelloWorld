# Configure minimum required version for CMake
cmake_minimum_required(VERSION 3.2)

# Declare project name and languages (all languages here)
project(HelloWorld)

# Setup variables: source and include paths
set(SRC_PATH "src")
set(INC_PATH "inc")
set(UIF_PATH "ui")
set(TST_PATH "test")

set(SRCFILES 
  
)

set(INCFILES 

)

set(SOURCES 
  ${SRCFILES}
  ${SRC_PATH}/main.cpp
)

set(INCLUDES 
  ${INCFILES}            
)

#This tells CMake to fib.c and name it fibonacci
add_executable(HelloWorld ${SOURCES} ${INCLUDES})   
