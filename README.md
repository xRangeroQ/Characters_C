# C ASCII Table Generator

A simple yet effective C program that visualizes the relationship between integer values and their corresponding ASCII characters. This project demonstrates basic loops, formatted output, and type casting in C.

## 📌 Overview

In C, characters are essentially small integers. This program iterates through the 8-bit integer range (0-255) and maps each numerical value to its character representation using the `%c` format specifier.

### Key Features:
- **Type Casting:** Explicitly converts `int` to `char` for safe representation.
- **Formatted Output:** Uses `%3d` padding to ensure a clean, aligned table in the terminal.
- **Full Range:** Covers both Standard ASCII (0-127) and Extended ASCII (128-255).
