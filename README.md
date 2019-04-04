# `assert 295 == "pure fun"`

## Introduction

This assigment gives some introduction to Python syntax and some practice with examples. Additionally it introduces `assert`ions, the closest analog to Racket's `check-expects` that we'll be using this quarter.

In the provided file `a1.py` implement the functions listed below (each function below has a corresponding stub in the provided `a1.py` file) and write additional `assert` tests to verify your solutions are correct. Once you're satisfied with your code submit the `a1.py` file to Canvas.

## Problems

1. (2 point) Write a function `absolute` that takes a number and returns the absolute value of that number (without using the python built-in function `abs`).
2. (3 points) Write a function `factorial` that takes a number, `n`, and returns the value of `n!`. Be sure to consider the boundary cases (i.e. 0 and 1).
3. (3 points) Write a function `every_other` that takes a list and returns a shorter list consisting of every other element of the original list, starting with the first (the 1st element, 3rd element, 5th element, etc.).
4. (3 points) Write a function `sum_list` that takes a list of numbers and returns the sum of the numbers.
5. (2 points) Write a function `mean` that takes a list of numbers and returns the mean of the list.
6. (3 points) Write a function `median` that takes an ordered list of numbers and returns the median of the list.
7. (4 points) Write a function `duck_duck_goose` that takes a list of names (strings) and plays 'duck duck goose' with it, knocking out every third name (wrapping around) until only two names are left. In other words, when you hit the end of the list, wrap around and keep counting from where you were.

    For example, if given this list `['Nathan', 'Sasha', 'Sara', 'Jennie']`, you'd first knock out Sara. Then first 'duck' on Jennie, wrap around to 'duck' on Nathan and 'goose' on Sasha - knocking him out and leaving only Nathan and Jennie. You may assume the list has 3+ names to start.
