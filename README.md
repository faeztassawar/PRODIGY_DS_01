# Data Visualization with Python

This repository contains Python code snippets for visualizing various aspects of population data using the matplotlib library. The code demonstrates how to load, filter, and visualize data related to population statistics.

## Files

### Population.csv
- This file contains population data for different countries over multiple years.

### Country.csv
- This file contains information about countries, including their regions and income groups.

### Division of Population of Pakistan.csv
- This file contains population data for different divisions of Pakistan, categorized by gender.

## Code Overview

The provided Python script (`PRODIGY_DS_01.ipynb`) performs the following tasks:

1. **Data Loading and Cleaning**: 
    - Loads population data from `Population.csv`.
    - Removes unnecessary columns like 'Indicator Name' and 'Indicator Code'.
    - Fills missing values using forward filling.
    - Removes any columns with all NaN values.

2. **Population Visualization**:
    - Visualizes the population of selected countries in 2022 using a bar chart.
    - Visualizes the population of China over the years.
    - Displays the total population per year using a horizontal bar chart.
    - Visualizes the distribution of regions using a bar chart.
    - Visualizes the distribution of income groups using a bar chart.
    - Visualizes the gender distribution of Pakistan division-wise using grouped bars.

## Instructions

To run the code:

1. Ensure you have Python installed on your system.
2. Install the required libraries: `numpy`, `pandas`, and `matplotlib`.
3. Place the data files (`Population.csv`, `Country.csv`, `Division of Population of Pakistan.csv`) in the same directory as the script.
4. Run the Python script (`PRODIGY_DS_01.ipynb`) using a Python interpreter.

---

Feel free to customize the code or data files according to your requirements!

---
