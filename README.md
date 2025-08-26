# Password_Generator
A basic python project
Password Generator in Python

-This project is a basic password generator written in Python.  
-It generates random, strong passwords using letters, numbers, and symbols.  
-The code is designed to run easily in Google Colab or locally.

 Features
- Generate random passwords of customizable length.
- Uses Python’s built-in `random` and `string` libraries.
- Simple and beginner-friendly code.

Code Explanation
- `random` → used to randomly pick characters.
- `string` → provides sets of characters (letters, digits, punctuation).
- `string.ascii_letters` → all A–Z and a–z.
- `string.digits` → numbers 0–9.
- `string.punctuation` → symbols like !@#$%.
- `random.choice(characters)` → picks a random character from the set.
- `''.join(...)` → joins all chosen characters into one password string.

Example Usage
-print(" 8-char password:", generate_password(8))
-print(" 12-char password:", generate_password(12))
-print(" 16-char password:", generate_password(16))
-This generates and prints random passwords of different lengths.

Learning Outcomes
- Learn how to use Python’s `random` and `string` modules.
- Understand how `''.join(...)` works to combine characters.
- Practice creating reusable functions in Python.

