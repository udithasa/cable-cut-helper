# Cable Cut Helper

A simple operator-friendly tool to calculate **precise cable cutting positions between printed meter marks** and generate **printable cut plans**.

During cable cutting operations, the printed meter markings on the cable rarely align exactly with required cut lengths. Operators often need to measure offsets such as:

- **0.3 m from 59**
- **0.7 m from 60**

When multiple cuts are required, calculating these positions repeatedly can be time-consuming and prone to errors.

This tool simplifies the process by automatically calculating and visualizing the cut positions in a way that matches how operators measure cables on the shop floor.

---

## Features

- Calculates cut positions automatically
- Displays the **exact meter reading**
- Shows **distance from both surrounding meter marks**
- Visual **meter bar with pointer marker**
- Supports **ascending or descending meter numbering**
- Handles **multiple cuts**
- Warns if the cable reel is **not long enough**
- Generates a **printable cut plan**
- Compact and detailed print formats
- Designed for **simple shop-floor usability**

---

## How It Works

Inputs:

- **Total cable length (y)**
- **Number of cuts (n)**
- **End meter value (E)**
- **Offset from end (e)**
- **Cable numbering direction**

The tool calculates the cut length:
x = y / n


It then determines the meter reading for each cut and displays:

- The cut reading
- The surrounding meter marks
- Distance from the lower mark
- Distance from the upper mark

---

## Example

Cut reading:
59.3 m

Displayed as:
Between 59 m and 60 m
0.3 m from 59
0.7 m from 60


This reflects the **actual measurement method used by operators** during cable cutting.

---

## Print Output

The tool generates a **printable cut plan** containing:

- Start point diagram
- Cable details
- Cut table with offsets
- Operator notes section
- Date and timestamp

This sheet can be printed and used directly during cutting operations.

---

## Purpose

This tool was created during training in a cable cutting section to explore a simple way to reduce manual calculations and improve clarity for operators.

Small process improvements like this can help make shop-floor tasks easier and reduce potential cutting errors.

---

## Technology

- HTML
- CSS
- JavaScript

Single-file application — no installation required.

---

## Live Demo

Once hosted using GitHub Pages, the tool can be accessed here:
https://udithasa.github.io/cable-cut-helper/


---

## Author

Uditha

## License

MIT License
