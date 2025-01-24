# capacitor-viewer
Interactive visualization tool for SMD MLCC voltage-capacitance distributions

## Overview
A quick reference tool for PCB designers to check realistic capacitance ranges for specific package sizes and dielectric types in multilayer ceramic capacitors (MLCCs).

## Usage
Visit [capacitor-viewer](https://joelsa.github.io/capacitor-viewer/) and select:
- Dielectric type (X7R, X5R, etc.)
- Package size (0603, 0805, etc.)
- View type (Distribution/Scatter)

![Capacitor Distribution Example](https://github.com/user-attachments/assets/88457f05-4edf-4cba-8d67-7ccc69342705)

## Data Source
Database derived from SQLite Databse at [JLC Parts](https://dougy83.github.io/jlcparts/#/) and visualized by a small python script. While component availability differs from other distributors like Mouser or DigiKey, the distributions probably remains representative for general design guidance.
