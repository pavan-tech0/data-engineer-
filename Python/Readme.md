
Python Learning Journey 🐍

A complete, beginner‑friendly repository documenting my step‑by‑step journey in learning Python from scratch.

This repo contains my notes, practice programs, solved challenges, and mini‑projects—all inspired by:

📘 Automate the Boring Stuff with Python (ATBS) – for practical beginner automation topics.

💻 Coddy.tech – for hands‑on coding challenges and structured Python practice.

This repository is designed to show consistent learning, clean coding habits, and beginner → intermediate Python mastery.

📚 Table of Contents

About This Repo

Learning Sources

Ideal Folder Structure

Beginner Python Projects

Coddy‑Style Exercises & Solutions

How to Use This Repo

Roadmap

License

🔥 About This Repo

This is my personal Python learning repository where I:

Practice core Python concepts every day

Build small automation scripts from ATBS

Solve hands‑on problems from Coddy.tech

Document my understanding through notes and examples

Prepare myself for future roles in Data Engineering, ML, and automation

📘 Learning Sources
1. Automate the Boring Stuff With Python

Topics I follow and practice:

Python basics

Flow control (loops, conditions)

Functions

Lists, dictionaries, tuples

File handling

Pattern matching (Regex)

Web scraping basics

Automation mini‑projects

2. Coddy.tech

I use Coddy.tech challenges to:

Strengthen logic building

Improve debugging skills

Practice small coding tasks

Solve real‑time scenario problems

📁 Ideal Folder Structure

python-learning-journey/
│
├── notes/
│ ├── python_basics.md
│ ├── data_types.md
│ ├── loops.md
│ ├── functions.md
│ ├── regex_notes.md
│ └── automation_notes.md
│
├── coddy-solutions/
│ ├── easy/
│ ├── medium/
│ └── hard/
│
├── exercises/
│ ├── 01_variables.py
│ ├── 02_conditions.py
│ ├── 03_loops.py
│ ├── 04_lists_dicts.py
│ ├── 05_functions.py
│ └── 06_file_handling.py
│
├── mini-projects/
│ ├── calculator_app/
│ ├── todo_list_cli/
│ ├── number_guessing_game/
│ ├── pdf_renamer_automation/
│ ├── folder_file_sorter/
│ └── password_generator/
│
├── automation-scripts/
│ ├── bulk_file_renamer.py
│ ├── excel_to_csv_converter.py
│ ├── image_downloader.py
│ └── folder_organizer.py
│
├── roadmap.md
├── requirements.txt
└── README.md

Beginner Python Projects

Below are recommended projects that show your learning progress clearly.

1. Number Guessing Game (Beginner)

Random number generator

User input handling

Looping logic

2. To‑Do List CLI App

Stores tasks in a file

Add/remove/view tasks

Great for file I/O practice

3. Simple Calculator App

Functions for +, −, ×, ÷

Input validation

4. Password Generator

Random strings

Optional strength levels

5. File/Folder Organizer (Automation)

Inspired by ATBS.

Reads directory

Moves files based on extension

Useful real‑life script

6. PDF / File Renamer Script

Rename files in bulk

Format: "invoice_001.pdf", etc.

📝 Coddy‑Style Exercises & Solutions

Below are sample exercises with solutions you can include in /coddy-solutions/.

⭐ Exercise 1: Sum of Digits

Input: A number like 1234
Output: 10

Solution:

def sum_of_digits(n: int) -> int:
    return sum(int(digit) for digit in str(n))


print(sum_of_digits(1234))  # 10
⭐ Exercise 2: Count Vowels

Input: "hello world"
Output: 3

def count_vowels(s: str) -> int:
    vowels = "aeiouAEIOU"
    return sum(1 for char in s if char in vowels)


print(count_vowels("hello world"))
⭐ Exercise 3: Find Maximum in List
def find_max(lst):
    maximum = lst[0]
    for item in lst:
        if item > maximum:
            maximum = item
    return maximum


print(find_max([10, 3, 77, 2]))
⭐ Exercise 4: Reverse a String Without Using Reverse()
def reverse_string(s: str) -> str:
    result = ""
    for char in s:
        result = char + result
    return result


print(reverse_string("python"))
⭐ Exercise 5: Check Palindrome
def is_palindrome(s: str) -> bool:
    s = s.lower().replace(" ", "")
    return s == s[::-1]


print(is_palindrome("Racecar"))
🚀 How to Use This Repo

Start with the notes folder

Practice using the exercises folder

Attempt Coddy.tech‑style challenges

Build confidence with beginner projects

Move on to automation scripts inspired by ATBS

Track your growth in roadmap.md

🛣️ Roadmap
Phase 1: Basics

Python syntax

Variables, data types

Loops, conditions

Phase 2: Intermediate

Lists, dictionaries, sets

Functions + modules

File handling

Phase 3: Projects

CLI apps

Automation scripts

Phase 4: Advanced topics

Regex

Web scraping

APIs

📜 License

MIT License – free to use and modify.

Happy Coding! Keep learning, keep building 🚀🐍
