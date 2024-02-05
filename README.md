# Libft [42 Project]
This 42 Project challenges us to build a library, that will accompany us over the Common Core.

## Overview
This is the 1º Project in the 42 Common Core. It serves the purpose to make us feel more comfortable with the C language as well as make a good library to accompany us over the course. Libft is a library that contains useful C functions for any project. Most of them are recreations from already existing standard libraries and some are useful new functions.

## Table of Contents
1. [Project Structure](#project-structure)
2. [Dependencies](#dependencies)
3. [How to Use](#how-to-use)
4. [Source file Example](#source-file-example)
5. [Contributing](#contributing)

## Project Structure
- `libft/`: Main directory containing the source code, header file and Makefile

## Dependencies
- None

## How to Use
To use the Libft, you need to:
1. Clone the repository
2. Go to the `libft` dir ```cd libft```
3. Run the command ```make```
4. In your source files include the header `#include "libft.h"`
5. Link the library to your program `gcc example.c -L[path_to_Libft_dir] -lft`

## Source file Example
Here's an example of a source file using one libft function
```c
/* Example: Using ft_strjoin to concatenate two strings */
#include "libft.h"

int main()
{
    char *str_joined;
    str_joined = ft_strjoin("Hello", "World");
    printf("%s\n", str_joined);
    return (0);
}
```
In this example the two strings, "Hello", "World", are joined creating one string, "Hello World", and then printed in terminal.

## Contributing
I welcome contributions. If you have any bug fix or improvement, feel free to submit a pull request on the repository.
