# Project Install Instructions

# Install

1. clone
2. pip install faker
3. pip install -r requirements.txt

# Testing

1. pytest
2. pytest --num_records=10
3. pytest --pylint --cov


# Implementation Steps

# Running the calculator via CLI   ( main.py )

python main.py  <number 1> <number 2> <operation>

# Example:

python3 main.py 5 3 add

# Output:

The result of 5 and 3 is equal to 8


# Command Pattern Calculator  ( dynamic_main.py )

## Overview
This project implements a **command-line calculator** using the **Command Pattern** and **Plugin Architecture**.
It supports dynamic command loading, unit testing, and exception handling.

## 🚀 Features
- Interactive REPL-based calculator
- **Command Pattern** for modularity
- **Plugin System** for dynamic command loading
- Supports `add`, `subtract`, `multiply`, `divide`
- **100% test coverage** with `pytest`

