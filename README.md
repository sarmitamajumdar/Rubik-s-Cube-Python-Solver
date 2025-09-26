# Rubik’s Cube Python Solver & Visualization

This project provides a **Python-based Rubik’s Cube solver** using [PyCuber](https://github.com/adrianliaw/PyCuber) and [Kociemba’s algorithm](http://kociemba.org/cube.htm). It also includes **2D and 3D interactive visualizations** using Matplotlib and Plotly, allowing step-by-step animations of cube states and solutions.

---

## Features

- **Scramble & Solve:** Apply custom scrambles and generate the solution sequence automatically.
- **Python Solver:** Uses Kociemba’s two-phase algorithm for efficient solving.
- **2D Visualization:** Display cube states in a clear 2D grid format.
- **3D Interactive Visualization:** Animate cube rotations step-by-step in 3D using Plotly.
- **Jupyter Notebook Ready:** Run all features interactively in `.ipynb` environments.

---

## Installation

```bash
pip install pycuber kociemba plotly

---

## For Python 3.10+, add this patch if you encounter Iterable errors:
import collections
import collections.abc
collections.Iterable = collections.abc.Iterable

---

### References

Kociemba’s Algorithm: http://kociemba.org/cube.htm
 – Two-phase solving method.

PyCuber: https://github.com/adrianliaw/PyCuber 
 – Python library for Rubik’s Cube representation.

---
### This project is MIT licensed.



