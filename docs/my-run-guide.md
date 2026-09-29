# Run guide: library demo

## Prerequisites

- JDK 17 or newer, with both `java` and `javac` available in the terminal
- Python 3.9 or newer
- Git, to clone this repository

## Run the demo

From the root of the repository, run:

    python3 run.py demo

## What the demo does

`run.py` compiles the Java library application into a temporary folder and runs `library.Main`.
The demo uses a fixed date (2026-09-01) so the output is always the same. It prints the student
and faculty borrowing limits, searches the catalog for `git`, lends the book "Git Essentials" to
the student Alex, and prints the loan receipt and due date. It then returns the book and prints
the return fee and the number of active loans.
