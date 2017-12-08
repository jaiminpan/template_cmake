# template_cmake

It's a template project for using cmake


#### Directory Structor

workspace
    |—— src
        |—— test
            |—— include
            |—— test.c
            |—— CMakeLists.txt
        |—— CMakeLists.txt
    |—— CMakeLists.txt
    |—— build          （CMake build dir 可任意指定）

#### Usage
```sh
># cd template_cmake
># mkdir build && cd build
># cmake ..
># make
```

