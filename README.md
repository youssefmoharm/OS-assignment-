# Assignment 2: Basic forks and C Style Development 💻

This repository contains my solutions for Lab 5 / Assignment 2. The programs demonstrate fundamental concepts in C development and process management.

## 📖 Overview

The programs show:

*   How the **fork()** system call creates parent and child processes.
*   How the *linker* combines multiple C files into a single executable program.
*   How the *loader* uses shared libraries (checked using the ldd command).

## 📁 Files

*   **moharm.c** 🔄
    *   An example using fork(). It creates a child process, and both the parent and child print their Process IDs (PIDs).

*   **moharm1.c** 🟩
    *   Contains the hello() function that prints a simple message.

*   **moharm2.c** 🔗
    *   Contains the main() function that calls hello(). When linked with moharm1.c, they form a single program.

*   **simple_program.c** 🔍
    *   A small program used to check which shared libraries are loaded using the ldd command.

*   **Makefile** 🔨
    *   Builds all the programs with a single make command.

*   **answers.txt** 📝
    *   Short written answers explaining what each exercise does and the roles of the linker and loader.

*   **LICENSE** 🔑
    *   The Boost Software  license for this project.

## 🛠 How to Compile

From inside the project folder, simply run:

```bash
make
