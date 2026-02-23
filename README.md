# Problem Solving with Python — Chapter 3: Replace Text with Emoji

This repository contains the chapter and active-learning exercise code associated with this chapter in the book *Problem Solving with Python: Using Computational Thinking in Everyday Life* by Michael D. Smith (2026), which is available from [MIT Press](https://mitpress.mit.edu/9780262383677/problem-solving-with-python/) and [Amazon](https://www.amazon.com/Problem-Solving-Python-Computational-Thinking/dp/0262552841/).

## Getting started

You will need:

- an integrated development environment (IDE)
- Python 3.10 or newer
- `pip` (usually included with Python)

If you need help getting started with an IDE, please read [my short introduction to "Understanding and Selecting an IDE"](https://ctps.io/select_ide.html).

## Cloning this repository

If you're using GitHub Codespaces, click the green "Code" button on this repo's page, select the tab "Codespaces," and click the "Create codespace on main."

Otherwise, in your IDE's terminal window, type the following commands:

```bash
git clone https://github.com/pswp-book/chap03.git
cd chap03
```

## (Optional) Create and activate a virtual environment

```bash
python -m venv .venv
# Windows
.\.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```

## Install dependencies

```bash
pip install -r requirements.txt
```

If there is no file `requirements.txt`, the code in this repository uses only the Python standard library.

## Reporting issues

If you find a problem in this chapter’s code (typo, bug, or mismatch with the book):

1.  Check the issues for this repo to see if it’s already reported.

2.  Open a new issue and include:
    *   The chapter number and section title (e.g., “Chapter 5, The game loop”)
    *   The filename, line number(s), and a short description of the problem.
    *   If something's wrong with the code's execution, please describe how you ran the program and the exeuction result.

## Short description of the repo's files

`script32.py`: a limited-functionality script that turns a story
into a theatrical script.

`txts`: Directory containing plaintext files used in the textbook,
exercises, and assignments.

`replace0.py`: an improved version of our script from Chapter 1, which
reads out the input text file.

`replace1.py`: a script that replaces an instance of "Cat" with "Gato".

`replace23.py`: a script that replaces _all_ instances of "Cat" with the
cat-with-wry-smile emoji.

`replace4.py`: a script that replaces _all_ instances of "Cat" and "Hat"
with fun emoji.

`replace5.py`: a script that doesn't use string-replace, but sets us up to
write our own function.

`replace6.py`: a script that illustrates a function definition,
implementation, and call site in pseudocode.

`replace7.py`: a script with our own string-replace function.

`replace32.py`: our complete script for solving the problem in Chapter 3.

`bookshelf*.py`: scripts that help us gain a deeper understanding of
abstraction and the utility of modules.

`import.py` and `module32.py`: scripts that help illustrate how control flows with module imports and the value of the special variable `__name__`.

`pythontutor.py`: used in ALE3.4, Step 1. Copy everything but the first
comment into the pythontutor.com edit box.

`scope.py` and `scope_broken.py`: scripts for talking about scope
in Python and how not to use global variables. Used in ALE08.

`ale3_5.ipynb` and `ale3_8.ipynb`: interactive Python notebooks for
ALEs 5 and 8, in case you'd rather try them in this form.

`ale09.py`: Script to be used in ALE 9.
