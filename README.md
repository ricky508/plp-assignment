# plp-assignment
assignment for python
Here’s a shorter version of the Python program:

```python
# Get user input
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter the operation (+, -, *, /): ")

# Calculate the result
if operation == '+':
    result = num1 + num2
elif operation == '-':
    result = num1 - num2
elif operation == '*':
    result = num1 * num2
elif operation == '/':
    result = num1 / num2 if num2 != 0 else "Error! Division by zero."
else:
    result = "Invalid operation."

# Print the result
print(f"{num1} {operation} {num2} = {result}")
```

**Summary:**  
This program asks for two numbers and an operation, performs the calculation, and outputs the result, handling errors gracefully.

**Example Output:**  
```
Enter the first number: 10
Enter the second number: 5
Enter the operation (+, -, *, /): +
10.0 + 5.0 = 15.0
```
