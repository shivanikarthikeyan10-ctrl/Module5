# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
~~~~~~~~~~~~~
class Demo:
    def __init__(self):
        print("Hello World!")

    def __del__(self):
        print("Hello from the __del__ method.")

# Create and delete the object
obj = Demo()
del obj
~~~~~~~~~~~~~~~~~
## 🧪 Output
<img width="1254" height="215" alt="WhatsApp Image 2026-05-28 at 9 14 12 PM" src="https://github.com/user-attachments/assets/fda1eef0-d4fb-4946-8740-d6d1c28a7b92" />


## Result
thus the program has verified

