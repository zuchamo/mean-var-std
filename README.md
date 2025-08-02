# 📊 Mean-Variance-Standard Deviation Calculator

This project solves a data analysis challenge from the [freeCodeCamp Data Analysis with Python certification](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/mean-variance-standard-deviation-calculator).  
It computes key statistical metrics (mean, variance, standard deviation, max, min, sum) across a **3×3 matrix**.

---

## 📂 File Overview

| Filename         | Purpose                                        |
|------------------|------------------------------------------------|
| `mean_var_std.py` | Defines the `calculate()` function             |
| `main.py`         | Simple test script to print calculation output |

---

## 🧠 Function Description

The `calculate()` function:
- Accepts a list of 9 numeric values
- Reshapes it into a 3×3 NumPy array
- Computes statistics across:
  - Columns (`axis=0`)
  - Rows (`axis=1`)
  - Entire matrix (flattened)
- Returns results as a dictionary of lists, like:

```python
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  ...
}
