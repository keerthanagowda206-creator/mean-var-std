# Mean-Variance-Standard Deviation Calculator

A freeCodeCamp Data Analysis with Python project.

## What it does

The `calculate()` function in `mean_var_std.py` takes a list of 9 numbers,
converts it into a 3x3 NumPy array, and returns a dictionary with the mean,
variance, standard deviation, max, min and sum:

- along each column (axis 0)
- along each row (axis 1)
- for the whole matrix (flattened)

If the list does not contain exactly 9 numbers, it raises:
`ValueError: List must contain nine numbers.`

## Example

    from mean_var_std import calculate
    print(calculate([0, 1, 2, 3, 4, 5, 6, 7, 8]))

## Run

    python main.py

## Requirements

- Python 3
- NumPy (`python -m pip install numpy`)
