# Intro-To-Python-Assignment
# Define the numbers
num1 = 8
num2 = 4

# Perform and display all operations
print(f"{num1} + {num2} = {num1 + num2}")  # Addition
print(f"{num1} - {num2} = {num1 - num2}")  # Subtraction
print(f"{num1} * {num2} = {num1 * num2}")  # Multiplication

# Handle division separately to check for division by zero
if num2 != 0:
    print(f"{num1} / {num2} = {num1 / num2}")  # Division
else:
    print("Division by zero is not allowed.")
