# call_by_reference
# Call By Value And Reference

This repository contains a C++ program that demonstrates how to swap two numbers using both call by value and call by reference. It provides explanations, code examples, and a brief algorithm to help you understand the concepts.

## Table of Contents
- [Introduction](#introduction)
- [Call By Value](#call-by-value)
- [Call By Reference](#call-by-reference)
- [Algorithm](#algorithm)
- [Output](#output)


## Introduction

In C++, there are two ways to pass arguments to functions: call by value and call by reference. Understanding the difference between these two methods is essential for efficient programming.

- **Call By Value**: In this approach, a copy of the variable is passed to the function. Any modifications made within the function do not affect the original variable outside the function.
- **Call By Reference**: In this approach, a reference to the variable is passed to the function. Any modifications made within the function directly affect the original variable outside the function.

## Call By Value

The `swapByValue` function in this code takes two integers as arguments and swaps them using call by value. However, the original variables remain unchanged after the function call.

```cpp
void swapByValue(int a, int b) {
    int temp = a;
    a = b;
    b = temp;
}
```

## Call By Reference

The `swapByReference` function takes two integers as arguments and swaps them using call by reference. This means that the original variables are modified directly within the function.

```cpp
void swapByReference(int &a, int &b) {
    int temp = a;
    a = b;
    b = temp;
}
```

## Algorithm

The algorithm for swapping numbers using both methods is as follows:

1. Initialize two integer variables, `num1` and `num2`.
2. Display the values of `num1` and `num2` before swapping.
3. Call the `swapByValue` function to swap `num1` and `num2` using call by value.
4. Display the values of `num1` and `num2` after swapping using call by value.
5. Reset the values of `num1` and `num2` to their original values.
6. Call the `swapByReference` function to swap `num1` and `num2` using call by reference.
7. Display the values of `num1` and `num2` after swapping using call by reference.

## Output

![image](https://github.com/Pranav18062004/Cpp-Call-by-value-reference/assets/79793482/a3752c20-d9cf-460f-b14d-2006ed6d0ef7)
