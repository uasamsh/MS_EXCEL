# Percentage Change Analysis Project

## Overview

This Excel project analyzes 20 years (2005–2024) of profit data. It calculates the
**Year-over-Year % Change** for each year using live formulas (not hardcoded values),
along with **summary statistics** and two **visualizations (charts)**.

## Screenshots

Below are screenshots of the project:

![Screenshot 1](Screenshot.png)


## Contents

- `Percentage_Change_Analysis.xlsx` — Main Excel file
  - **Sheet: Profit Data**
    - Year, Profit ($), % Change (formula-based)
    - Summary Statistics: Average Profit, Highest Profit, Lowest Profit, Average % Change, Highest % Change, Lowest % Change, Total Growth (2005–2024)
    - Line Chart: Profit Trend (2005–2024)
    - Bar Chart: Year-over-Year % Change

## Formulas Used

- `% Change = (Current Year Profit - Previous Year Profit) / Previous Year Profit`
- `AVERAGE()`, `MAX()`, `MIN()` for summary statistics

## How to Use

1. Download and open `Percentage_Change_Analysis.xlsx` in Microsoft Excel.
2. Profit values (column B) are shown in blue font — these are the editable input cells.
3. The % Change column and all summary statistics recalculate automatically when the
   Profit values are updated.

> Note: The screenshots above will display correctly once you upload them to this same
> folder on GitHub. Update the file names in this README if your screenshot files have
> different names.

## Author

Uzma Ejaz
