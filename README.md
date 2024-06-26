# 42 Push Swap Project

Welcome to the 42 Push Swap Project repository! This project is part of the 42 curriculum, and its goal is to sort data on a stack with a limited set of operations. The challenge is to sort the stack using the fewest number of moves.

## Table of Contents
- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Requirements](#requirements)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [Grade](#grade)

## Introduction

The Push Swap project is designed to help students understand algorithmic thinking and optimization by sorting data using two stacks and a limited set of operations. This project requires a deep understanding of sorting algorithms, data structures, and algorithmic optimization.

## Project Objectives

- Implement sorting algorithms that use two stacks.
- Optimize the number of moves to sort the stack.
- Handle different edge cases and input sizes.
- Develop a robust understanding of stack operations.

## Requirements

- A Unix-based operating system (Linux or macOS).
- GCC compiler.
- Basic understanding of C programming and data structures.

## Project Structure

Here's a brief overview of the project structure:

```
.
├── srcs
| ├── check_index.c
| ├── check_postarget.c
| ├── check_size.c
| ├── check_values.c
| ├── duplicates.c
| ├── error.c
| ├── init_stack.c
│ ├── main.c
| ├── numcheck.c
| ├── opshifting.c
| ├──  push_swap.h
| ├── reverse_rotate.c
| ├── rotate.c
| ├── rotatenreverserotutils.c
| ├── swap.c
| ├── swap2.c
│ └── utils.c
├── bonus
| ├── check_index_bonus.c
| ├── check_postarget_bonus.c
| ├── check_size_bonus.c
| ├── check_values_bonus.c
| ├── duplicates_bonus.c
| ├── error_bonus.c
| ├── get_next_line_bonus.c
| ├── get_next_line_bonus.h
| ├── get_next_line_bonus_utils.c
| ├── init_stack_bonus.c
│ ├── main_bonus.c
| ├── numcheck_bonus.c
| ├── opshifting_bonus.c
| ├──  push_swap_bonus.h
| ├── reverse_rotate_bonus.c
| ├── rotate_bonus.c
| ├── rotatenreverserotutils_bonus.c
| ├── swap_bonus.c
| ├── swap2_bonus.c
│ └── utils_bonus.c
├── Makefile
└── README.md
```

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/joaoped2-42PORTO/42-push_swap.git
    cd 42-push_swap
    ```

2. **Compile the Project**:
    ```bash
    make
    ```

    This will create the necessary executable file (e.g., `push_swap`).

## Usage

To use the `push_swap` program, provide a list of integers as arguments. The program will output the sequence of moves to sort the stack.

1. **Run the Program**:
    ```bash
    ./push_swap 3 2 1
    ```

2. **Checker Program**:
    Additionally, you may use the `checker` program to verify if your sorting is correct (if implemented).

    ```bash
    ./checker 3 2 1
    ```

    Followed by inputting the sequence of operations generated by `push_swap`.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or submit a pull request. Please ensure that your contributions adhere to the coding standards and guidelines of the project.


## Acknowledgments

- The 42 Network for providing the inspiration and resources for this project.
- The C programming community for their excellent documentation and support.
- All contributors who have helped improve this project.

## Grade

- Norminette: Ok!
- Grade: 125/100

---

Happy coding!
