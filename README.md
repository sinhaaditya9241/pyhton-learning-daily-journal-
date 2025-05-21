# 🧾 Module 9: Regular Expressions in Python (re module)

This module introduces **Regular Expressions (RegEx)** — a powerful tool for pattern matching and text manipulation in Python using the built-in `re` module. Regular expressions are especially useful in tasks like data validation, cleaning, scraping, and parsing text.

---

## 🧠 Topics Covered

### 🔹 Regular Expression Basics
- **Introduction to Regular Expressions**
  - What are regular expressions?
  - Syntax and use-cases in real-world programming

### 🔍 Core Functions from `re` Module
- **`match()` and `findall()`**
  - `match()` checks for a match only at the beginning of a string
  - `findall()` returns all matches in a string as a list

- **`search()`**
  - Scans through the string and returns the first match

- **`sub()`**
  - Substitutes matched patterns with a replacement string

---

### 🧩 Regex Syntax: Characters and Sequences

- **Character classes**
  - `[a-z]`, `[0-9]`, `[A-Za-z]`, etc.

- **Special sequences**
  - `\d`, `\w`, `\s`, `\b`, etc.

- **Quantifiers and anchors**
  - `+`, `*`, `?`, `{m,n}`, `^`, `$`

- **Escape characters and raw strings**
  - Importance of `r''` syntax in Python regex

---

## 📂 Files in This Module

| File Name             | Description                                  |
|----------------------|----------------------------------------------|
| `regex_intro.py`      | Introduction and basic pattern examples      |
| `regex_match_find.py`| Using `match()` and `findall()`              |
| `regex_search.py`     | Demonstrates `search()` for finding patterns |
| `regex_sub.py`        | Pattern substitution using `sub()`           |
| `regex_chars.py`      | Character classes and special sequences      |

---

## ✅ Key Takeaways

- Regular expressions are essential for **text processing**, **data cleaning**, and **log parsing**.
- Python’s `re` module provides powerful functions like `search()`, `findall()`, `match()`, and `sub()`.
- Mastering regex makes you significantly more efficient when working with **strings**, **files**, and **web data**.

---

💡 *Regular expressions are widely used in data science, web scraping, and automation scripts — mastering them will boost your productivity and coding skills!*
