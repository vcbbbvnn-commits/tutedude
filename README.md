# Assignment 1 — Basic Mathematical Operations

**Description**

This small Python program prompts the user to enter two numbers and then computes and displays the results of the four basic arithmetic operations: addition, subtraction, multiplication, and division.

**Files**

- `q1.py` — The program that reads two numbers from the user and prints the results.

**Usage**

From the `assignment1` folder run:

```bash
python q1.py
```

If you're using the workspace virtual environment, run:

```bash
C:/Users/USER/OneDrive/Desktop/tutedude/.venv/Scripts/python.exe q1.py
```

Then enter the two numbers when prompted:

```
Enter the first number: 10
Enter the second number: 5
```

# Assignment 1 — Exercises

**Description**

- `q1.py`: Prompts the user for two numbers and computes the four basic arithmetic operations: addition, subtraction, multiplication, and division.
- `q2.py`: Prompts the user for a first name and last name, then prints a welcome message using the full name.

**Files**

- `q1.py` — Reads two numbers and prints results for addition, subtraction, multiplication, and division.
- `q2.py` — Reads first and last names and prints a greeting.

**Usage**

From the `assignment1` folder run:

```bash
python q1.py
```

```bash
python q2.py
```

If you're using the workspace virtual environment, run:

```bash
C:/Users/USER/OneDrive/Desktop/tutedude/.venv/Scripts/python.exe q1.py
C:/Users/USER/OneDrive/Desktop/tutedude/.venv/Scripts/python.exe q2.py
```

When prompted, enter the required input values.

**Examples**

q1 example run:

```
Enter the first number: 10
Enter the second number: 5

Results:
Addition: 15.0
Subtraction: 5.0
Multiplication: 50.0
Division: 2.0
```

q2 example run:

```
Enter your first name: Ada
Enter your last name: Lovelace
Hello, Ada Lovelace! Welcome!
```

**Notes & Suggestions**

- Both scripts currently assume valid input. Non-numeric input to `q1.py` or division by zero will raise an error.
- If you'd like, I can update `q1.py` to:
	- validate numeric input and re-prompt on invalid values,
	- handle division-by-zero gracefully (show a message instead of crashing),
	- and add a small test harness or examples.

Tell me if you want those improvements and I'll implement them.
