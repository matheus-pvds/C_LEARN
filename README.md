# C_LEARN — "Hello, World!" in C

![C](https://img.shields.io/badge/C-C89/C99-A8B9CC?logo=c&logoColor=white)
![GCC](https://img.shields.io/badge/GCC-13-6DB33F?logo=gnu&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

A minimal beginner's C programming exercise that prints `"Hello, world!"` to stdout. The project includes unused variable declarations for learning purposes (char, int, double types).

## Features

- Prints `"Hello, world!"` to standard output
- Demonstrates basic C syntax: includes, main function, variable declarations, printf
- Unused variable declarations showcase multiple data types

## Tech Stack

C (C89/C99), GCC/Clang

## Architecture

Single-file program (`main.c`):

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    char grade = 'A';
    int age = 54;
    double smh = 34.5;
    printf("Hello, world!");
    return 0;
}
```

## Build & Run

```bash
gcc main.c -o main
./main
```

## License

MIT
