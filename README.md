# C Libraries

This repository contains a collection of C libraries for various purposes.
Each library is designed to be modular and reusable in different projects.

## Libraries

### 1. String Utilities

A set of functions for common string operations such as concatenation, splitting, stripping, and duplicating.

### 2. Data Structures

Implementations of common data structures, like stacks.

### 3. File I/O

Functions to simplify reading from files (e.g. reading the next line from a file).

### 4. Error handling

A predefined struct for errors, and a macro that sets the error code, and the error message (such that it includes the file name, line number and function name of the code that set the error).

## Getting Started

### Prerequisites

- clang
- Make

### Usage

Include the header files of the libraries you need in your C project:

```c
// #include "stringutils.h" (unimplemented)
// #include "fileutils.h" (unimplemented)
#include "stack.h"
#include "error.h"
#include "require.h"
#include "trycatch.h"
```

Use the `Make` rules that build the test scripts in each submodule as a guide for linking against the relevant library.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Contact

For any questions or suggestions, please open an issue or contact the repository owner.
