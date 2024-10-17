# EXP-2: Program Structure and Data Types in C++

This repository contains examples and explanations related to program structure and various data types in C++. Understanding the fundamental data types and program structure is essential for writing clear and efficient C++ programs.

## Table of Contents

- [Introduction](#introduction)
- [Topics Covered](#topics-covered)

## Introduction

In C++, the program structure defines the overall layout of a C++ program, including how the code is organized. Additionally, C++ offers several built-in data types that are used to store different types of values in variables. This repository provides code examples demonstrating the usage of these data types and how to structure a basic C++ program.

## Topics Covered

### 1. **Basic Program Structure**

A typical C++ program consists of the following components:
   - **Headers**: Includes necessary libraries like `<iostream>`.
   - **Main Function**: The entry point of every C++ program.
   - **Variable Declaration**: Defining variables and constants.
   - **Statements**: Instructions that tell the program what to do.
   - **Return Statement**: The `main()` function returns an integer, typically 0 for success.

### 2. **Data Types**

#### a. **Primitive Data Types**
   - **Integer (`int`)**: Stores whole numbers.
   - **Floating-point (`float` and `double`)**: Stores decimal numbers.
   - **Character (`char`)**: Stores a single character.
   - **Boolean (`bool`)**: Stores true or false values.
   
#### b. **Derived Data Types**
   - **Arrays**: A collection of elements of the same type stored in contiguous memory locations.
   - **Pointers**: Variables that store the memory address of another variable.

#### c. **User-defined Data Types**
   - **Structures (`struct`)**: Custom data types that group different variables under one name.
   - **Enumerations (`enum`)**: Defines a set of named integer constants.

### 3. **Variable Declaration and Initialization**

   In C++, variables must be declared before use. They can also be initialized during declaration:
   ```cpp
   int a = 5; // integer variable
   float pi = 3.14; // floating-point variable
   char grade = 'A'; // character variable
