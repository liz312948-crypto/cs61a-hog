# CS61A Hog

A Python implementation of the CS61A Hog project. This repository includes the full game logic, the provided test suite, and GUI assets for interactive play.

## Project Overview

Hog is a two-player dice strategy game. This project implements the core simulator, special scoring rules, strategy evaluation, and a simple GUI interface.

## What I Built

- Implemented the core turn-based game loop and score update flow in Python
- Completed special rule handling such as Pig Out, Free Bacon, Boar Brawl, and Sus Fuss
- Built strategy helpers for repeated simulation and average-score evaluation
- Passed the course test suite to verify game logic correctness
- Kept the project runnable with both command-line and GUI-related files

## Tech Stack

- Python
- Functional programming patterns
- Basic simulation and strategy evaluation
- Test-driven verification with the provided course tests

## Project Structure

- `hog.py`: core game logic and strategy functions
- `dice.py`: dice helpers
- `hog_ui.py` / `hog_gui.py`: interface-related entry points
- `tests/`: provided test suite and utilities
- `gui_files/`: static assets for the GUI version

## How to Run

Run the main project logic:

```bash
python hog.py
```

Run the GUI-related entry point:

```bash
python hog_gui.py
```

## Why This Project Matters

This project reflects my ability to translate game rules into executable logic, handle edge cases, and verify correctness with tests. It is also one of the earliest projects where I independently completed a full Python implementation from rules to runnable code.
