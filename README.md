# Workflow

This repository contains a simple C++ project with a CMake build system.

## Overview

The project consists of a single source file `main.cpp` and a CMakeLists.txt file for building the executable.

## Installation and Usage

### Prerequisites

- CMake (minimum version 3.10)
- C++ compiler (supporting C++11 or later)

### Building

1. Clone the repository:

    ```bash
    git clone https://github.com/himanshunanda22/Workflow.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Workflow
    ```

3. Configure the project using CMake:

    ```bash
    cmake .
    ```

4. Build the project:

    ```bash
    cmake --build .
    ```

### Running

After building the project, you can execute the generated executable:

```bash
./hello_world
```

### What it does ?

main.cpp: This is the main source code file or C++ program. It contains the actual implementation of program, including any functions, classes, or logic necessary to achieve its intended functionality. In this specific case, it simply prints "Hello, world!, This is SRN PES2UG21CS915" to the console.

CMakeLists.txt: This is the CMake build script for your project. CMake is a cross-platform build system that generates native build files (like Makefiles or Visual Studio solutions) based on platform and compiler specifications. The CMakeLists.txt file specifies how to build your project, including any source files, dependencies, compiler options, and output targets. In your case, it sets the minimum required CMake version, defines a project with a specific name, and declares an executable target named hello_world built from main.cpp.
