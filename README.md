# I-O-with-Python
"""
Sanyerlis Camacaro - CSC235 - Sancamac@uat.edu Assignment: I/O with Python

This code demonstrates how to:
Add I/O to your application.
Add at least one string data type in a variable to your tutorial application.
Add at least one numeric data type in a variable to your tutorial application.
Upgrade your Python Tutorial application to use I/O.
The Input / Output must make sense for the application, not just be a demo of input and output.
Create an even better user experience.
Over comment your code.
"""
# Welcome User.
print("Welcome to the Python Print Function Interactive Tutorial!")

# Explains the Program to the user.
print("\nThis program will guide you through the basics of using the 'print' function in Python.")
print("To proceed, simply follow the prompts and instructions.")
print("\nLet's get started!")

# First, we'll explain what the 'print' function is.
print("\nIn Python, the 'print' function is used to output text, variables, and other information to the console.")

# Now, we'll show a basic example of how to use 'print'.
print("\nHere's an example of using 'print' to output the phrase 'Hello, World!':")
print("print('Hello, World!')")

# Let's ask the user to try using 'print' themselves.
user_input = input("\nNow it's your turn! Try to use the 'print' function to output your own message.\nEnter a message: ")

# We'll output whatever the user entered.
print("\nHere's what you entered:")
print(user_input)

# Finally, let's explain that 'print' can be used with variables as well.
user_name = input("\nGreat job! Now, let's print your name using a variable. Please enter your name: ")
print("\nHello, " + user_name + "! This message was output using the 'print' function and a variable.")

# Now let's introduce basic I/O operations.
print("\nMoving on to basic I/O operations. In Python, we can easily read from and write to files.")

# Let's create a file and write something to it.
print("\nLet's create a new text file and write your name into it.")
with open('username.txt', 'w') as f:
    f.write(user_name)
print("\nWe've created a new text file named 'username.txt' and wrote your name into it.")

# Now, we'll read the content of the file.
print("\nNow, let's read the content of the 'username.txt'.")
with open('username.txt', 'r') as f:
    content = f.read()
print("\nThe content of 'username.txt' is: " + content)

# Next, we'll introduce the concept of string and numeric data types.
print("\nNow, let's look at string and numeric data types in Python.")

# String data type.
string1 = "Python "
string2 = "Tutorial"
print("\nString data type: The variables 'string1' and 'string2' are of string data type.")
print("We can concatenate them as follows:")
print(string1 + string2)

# Numeric data type.
num1 = 10
num2 = 20
print("\nNumeric data type: The variables 'num1' and 'num2' are of numeric data type.")
print("We can perform arithmetic operations on them.")
print("For instance, '10' + '20' = ")
print(num1 + num2)

print("\nAnd that's an overview of using the 'print' function, performing basic I/O operations,")
print("and using string and numeric data types in Python!")
print("\nThank you for participating in this tutorial.")

# This is the end of the program.
