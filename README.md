# 🐍 Python Fundamentals — Sessions 1 & 2

> This is the **very first step** of my Python and Machine Learning journey as a CS student. This notebook covers everything from printing your first line of code to writing real programs using loops and conditions — built from scratch, concept by concept.

---

## 📖 About This Notebook

This notebook is where it all began. Before touching Machine Learning or Data Science, you need a strong Python foundation — and that is exactly what these two sessions are about. Every topic here is a building block. Skip any one of them, and things get harder later.

The notes inside are written in a mix of English and Urdu because learning in your own language makes concepts click faster. The code is clean, simple, and written to understand — not just to run.

This is **Session 1 and Session 2** of an ongoing learning series. More notebooks will follow as the journey continues.

---

## 🗂️ What Is Covered — Topic by Topic

### 🔹 Session 1 — The Absolute Basics of Python

**1. The `print()` Function**
The very first thing any Python programmer learns. Covers how to print text, numbers, and multiple values together. Also covers the `sep` parameter (to change what goes between values) and the `end` parameter (to control what happens at the end of a line).

**2. Data Types**
Python has several built-in types and every value you work with belongs to one of them:
- `int` — whole numbers (e.g. `5`, `100`)
- `float` — decimal numbers (e.g. `3.14`, `7.8`)
- `bool` — `True` or `False`
- `str` — text / strings (e.g. `"hello"`)
- `complex` — complex numbers (e.g. `3+4j`)
- `list` — ordered, changeable collection (e.g. `[1, 2, 3]`)
- `tuple` — ordered, unchangeable collection (e.g. `(1, 2, 3)`)
- `set` — unordered, unique values (e.g. `{1, 2, 3}`)
- `dict` — key-value pairs (e.g. `{'name': 'ali'}`)

> 📌 Note: Python does NOT have a separate character data type. A single character is just a string of length 1.

**3. The `type()` Function**
Lets you check what data type any value belongs to at any point in your code. Very useful for debugging.

**4. Variables**
Variables are containers that hold values for later use. Python uses **dynamic typing** — you don't need to declare the type, Python figures it out. It also uses **dynamic binding** — the same variable can hold different types at different times.

**5. Multiple Assignment**
Python lets you assign values to multiple variables in a single line: `a, b, c = 1, 2, 3`

**6. User Input**
The `input()` function lets your program take input from the user at runtime. Since `input()` always returns a string, you cast it using `int()` or `float()` when you need numbers.

**7. Literals**
Different ways to write fixed values in Python:
- Binary: `0b1010`
- Octal: `0o677`
- Decimal: `262733`
- Float: `234.789`
- Complex: `34+9j`

---

### 🔹 Session 2 — Operators, If-Else & Loops

**1. Arithmetic Operators**
The basic math operations in Python:

| Operator | Meaning | Example |
|---|---|---|
| `+` | Addition | `3 + 8 = 11` |
| `-` | Subtraction | `5 - 3 = 2` |
| `*` | Multiplication | `5 * 3 = 15` |
| `/` | Division | `5 / 3 = 1.666...` |
| `//` | Integer Division | `10 // 2 = 5` (removes decimal) |
| `%` | Modulus | `5 % 3 = 2` (gives remainder) |
| `**` | Power | `5 ** 2 = 25` |

**2. Relational Operators**
Used to compare two values. Always return `True` or `False`:
`>`, `<`, `>=`, `<=`, `==` (equal to), `!=` (not equal to)

**3. Logical Operators**
Used to combine conditions:
- `and` — both conditions must be True
- `or` — at least one condition must be True
- `not` — flips True to False and False to True

**4. Bitwise Operators**
Work on the binary (0s and 1s) representation of numbers:
- `&` — AND: both bits must be 1
- `|` — OR: at least one bit must be 1
- `^` — XOR: bits must be different
- `~` — NOT: flips all bits

**5. Assignment Operators**
Used to assign or update variable values: `=`, `+=`, `-=`, `*=`, etc.

**6. Membership Operators**
Check whether a value exists inside a sequence:
- `in` — returns `True` if found
- `not in` — returns `True` if not found

Works with strings, lists, tuples, and more.

**7. If / Elif / Else — Conditional Logic**
The core of decision-making in Python. Lets your program take different paths depending on conditions. Covers `if`, `elif` (else if), and `else` blocks.

**8. While Loop**
Repeats a block of code as long as a condition is True. Used here to build a multiplication table printer. Also covers the `else` block on a while loop (runs when the condition finally becomes False).

**9. For Loop**
Used to iterate over a sequence — a range of numbers, characters in a string, or items in a list. Uses `range()` to generate number sequences.

**10. Modules**
Python's built-in modules extend what your code can do without writing everything yourself:
- `math` — mathematical functions
- `random` — generating random numbers
- `datetime` — working with dates and times
- `keywords` — all 33 reserved Python keywords

---

## 🧪 Mini Projects Built in This Notebook

These are small but real programs — not just print statements. Each one applies multiple concepts from the sessions above:

- 🔐 **Login System** — takes email and password as input, validates using `if-else` with `and` logic
- 🔢 **3-Digit Sum Finder** — extracts individual digits using `%` and `//`, then adds them
- 📉 **Minimum Number Finder** — compares 3 user-inputted numbers using `if-elif-else`
- 🎲 **Guess the Number Game** — generates a random number, loops until the user guesses correctly using `while` + `random` module

---

## 🚀 How to Run This Notebook

1. Clone this repo or download the `.ipynb` file
2. Open it in [Jupyter Notebook](https://jupyter.org/) or [VS Code](https://code.visualstudio.com/) with the Jupyter extension installed
3. Run cells one by one — cells with `input()` will wait for you to type something before continuing

```bash
# Install Jupyter if needed
pip install notebook

# Launch the notebook
jupyter notebook python_upto_ifelse_and_loops.ipynb


## 🛠️ Tools & Environment

- **Language:** Python 3.x
- **Platform:** Jupyter Notebook / VS Code
- **Libraries Used:** `random` (built-in standard library — no installation needed)


## 🎯 My Learning Goals

- [x] Start Python from absolute zero ✅
- [ ] Complete Python fundamentals (functions, OOP, file handling)
- [ ] Learn NumPy, Pandas, Matplotlib
- [ ] Start solving problems on Kaggle
- [ ] Work towards **Kaggle Grandmaster** 🏆


## 👤 Author

**Mehr Ali** — CS Student (4th Semester) | Aspiring ML Engineer & Kaggle Grandmaster

> *"Every expert was once a beginner. Every pro was once an amateur."* — Keep going! 💪
