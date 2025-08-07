
# Python Practice Tasks 🐍

This repository contains two beginner-level Python tasks that demonstrate basic concepts like user input, conditional statements, loops, and simple arithmetic.

---

## ✅ Task 1: Check if a Number is Even or Odd

### 🔹 Problem Statement:
Write a Python program that:
1. Takes an integer input from the user.
2. Checks whether the number is even or odd using an `if-else` statement.
3. Displays the result accordingly.

### 🧪 Sample Output:

### 💡 Python Code:
```python
# Task 1: Check if a Number is Even or Odd

num = int(input("Enter a number: "))

if num % 2 == 0:
    print(f"{num} is an even number.")
else:
    print(f"{num} is an odd number.")
The sum of numbers from 1 to 50 is: 1275
# Task 2: Sum of Integers from 1 to 50 Using a Loop

total = 0

for num in range(1, 51):
    total += num

print("The sum of numbers from 1 to 50 is:", total)

