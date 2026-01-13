# Python_Basics
This repository contains small Python projects I created as a beginner to practice coding and showcase my skills.
name="Maryam"
print(f"Hello!{name}")
print("\nEven Odd Checker")
num=int(input("Enter number:"))
if num%2==0:
    print("Even")
else:
     print("Odd")
print("Calcus")
# Day 4 – Simple Calculator
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
op = input("Enter operation (+, -, *, /): ")

if op == "+":
    print(f"Result: {num1 + num2}")
elif op == "-":
    print(f"Result: {num1 - num2}")
elif op == "*":
    print(f"Result: {num1 * num2}")
elif op == "/":
    if num2 != 0:
        print(f"Result: {num1 / num2}")
    else:
        print("Cannot divide by zero")
else:
    print("Invalid operation")
# Day 5 – Number Guessing Game
import random

number = random.randint(1, 10)  # Random number between 1–10
guess = int(input("Guess the number (1-10): "))

if guess == number:
    print("Congratulations! You guessed it right!")
else:
    print(f"Wrong! The number was {number}.")
# Day 6 – Multiplication Table
num = int(input("Enter a number: "))

print(f"Multiplication Table for {num}:")
for i in range(1, 11):
    print(f"{num} x {i} = {num * i}")
  
