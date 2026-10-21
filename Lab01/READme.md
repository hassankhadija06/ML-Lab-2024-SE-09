
# Lab 01: Python Fundamentals

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

Solutions to **Lab 01** of the Machine Learning lab (Semester 5). The lab is a warm-up in core Python (strings, lists, dictionaries, functions and conditionals) that the later machine learning labs build on.

**Author:** Syeda Khadija Hassan (2024-SE-09)
**Department:** Software Engineering, University of Azad Jammu & Kashmir, Muzaffarabad

---

## Contents

| File | Description |
|:--|:--|
| [`Lab01.ipynb`](Lab01.ipynb) | Notebook with all 10 tasks, the 3 bonus challenges and the conclusion |
| `README.md` | This file |

## Tasks Covered

| # | Task | Concept |
|:--:|:--|:--|
| 01 | Calculate 7 to the power of 4 | `**` operator |
| 02 | Split `"Hi there Sam!"` into a list | `str.split()` |
| 03 | Print a sentence about Earth's diameter | `str.format()` |
| 04 | Grab `'hello'` from a nested list | Chained indexing |
| 05 | Grab `'hello'` from a nested dictionary | Keys and indices |
| 06 | Difference between a tuple and a list | Mutability |
| 07 | Get the domain from an email address | Functions, `split('@')` |
| 08 | Check if `"dog"` is in a string (case-insensitive) | `in`, `.lower()` |
| 09 | Count how many times `"dog"` occurs (case-insensitive) | `str.count()` |
| 10 | `caught_speeding(speed, is_birthday)` | `if / elif / else`, edge cases |

### Bonus Challenges

| # | Challenge | Concept |
|:--:|:--|:--|
| 1 | Count `"dog"` even with punctuation (`"dog,"`, `"dog!"`) | `strip(string.punctuation)` |
| 2 | `is_palindrome(word)` | Slicing `[::-1]` |
| 3 | Store 5 students as a list of dictionaries and print the topper | `max()` with `key=` |

## How to Run

1. Make sure Python 3 is installed.
2. Install Jupyter if you do not have it:
   ```bash
   pip install notebook
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Lab01.ipynb
   ```
4. Run everything from the top with **Kernel → Restart & Run All**.

No extra libraries are needed. The notebook only uses Python's built-in features and the standard `string` module.

## Notes

- Each task has its own code cell, and the output is visible directly below it.
- Task 10 also checks the birthday edge cases (for example, 65 mph on a birthday is treated as 60, so no ticket).
- The Bonus 1 function counts whole words only, so `"dogs"` and `"hotdog"` are not counted.

## Conclusion

This lab covered the basics of Python: arithmetic, string methods and formatting, nested indexing, mutable and immutable types, functions and conditional statements. These are the building blocks for the data-handling code used in later Machine Learning labs.
