# Moglix Assessment - Longest Valid Parentheses

## Overview

This repository contains my solution to the **Longest Valid Parentheses** problem in Java.

The goal is to find the length of the longest valid (well-formed) parentheses substring.

## Solution

I used a **Stack** to store the indices of parentheses while traversing the string.

- Push the index of every `'('`.
- When `')'` is found, pop from the stack.
- Calculate the length of the current valid substring.
- Keep track of the maximum length found.

This approach efficiently handles all valid and invalid parentheses combinations.

## Time & Space Complexity

- **Time Complexity:** O(n)
- **Space Complexity:** O(n)

## Example

**Input**
```
(() 
```

**Output**
```
2
```

**Input**
```
)()())
```

**Output**
```
4
```

## How to Run

Compile the program:

```bash
javac Main.java
```

Run the program:

```bash
java Main
```

## Author

**Vishal Singh**

GitHub: https://github.com/vishhh443
