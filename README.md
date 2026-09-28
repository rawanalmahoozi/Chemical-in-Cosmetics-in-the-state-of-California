# Chemical in Cosmetics in the State of California

## Problem Statement

The California cosmetic chemical disclosure dataset contains 112,870 records reported between 2009 and early 2020. The data shows differences in the number of reported chemicals across product categories, changes in disclosure volume over time, and differences in product discontinuation. This project analyzes the reported chemicals, product categories, reporting trends and discontinuation information to identify if patterns exist and examine whether the number and type of reported chemicals are associated with product characteristics and discontinuation.

## Executive Summary

This project uses Exploratory Data Analysis (EDA) to investigate **112,870 chemical disclosure records** from 2009 to early 2020. The data was cleaned and analyzed using Python, Pandas, and visualizations to examine product categories, chemical frequency, and discontinued products.

The analysis found that **88.57%** of records had no discontinued date, while **11.43%** were associated with a discontinued date. **Titanium dioxide** was the most frequently reported chemical, followed by respirable silica, retinol/retinyl esters, BHA, and mica.

Overall, the analysis identified differences in chemical reporting across categories and between discontinued and non-discontinued products. However, these patterns show **association rather than causation**.

## File Directory

| File            | Description                              |
| --------------- | ---------------------------------------- |
| `notebooks/`    | Jupyter Notebook containing the analysis |
| `presentation/` | Project presentation                     |
| `data.zip`      | Dataset used for the analysis            |
| `README.md`     | Project documentation                    |

## Data and Data Dictionary

The dataset contains California cosmetic chemical disclosure records from **2009 to early 2020**.


### Main Features

| Feature                  | Description                  |
| ------------------------ | ---------------------------- |
| `ProductName`            | Cosmetic product name        |
| `PrimaryCategory`        | Product category             |
| `ChemicalName`           | Reported chemical            |
| `InitialDateReported`    | Initial reporting date       |
| `DiscontinuedDate`       | Product discontinuation date |

### Engineered Feature

* `IsDiscontinued` — identifies whether a product has a recorded discontinued date.

## Conclusions and Recommendations

* Most records were not associated with discontinued products.
* Titanium dioxide was the most frequently reported chemical.
* Chemical reporting patterns varied across product categories.
* Differences between discontinued and non-discontinued products were observed, but they do not prove that specific chemicals caused discontinuation.

## Further Research

Future analysis could investigate:

* Chemical patterns within individual product categories.
* Changes in chemical reporting over time.
* The number of chemicals reported per product.
* Statistical relationships between chemicals and discontinuation.

## Visualizations

Key visualizations include:

* Discontinued vs. non-discontinued products
* Most frequently reported chemicals
* Chemical reporting by product category
* Chemical patterns in discontinued vs. non-discontinued products

## Sources

* [California Safe Cosmetics Program](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FWunmi-O%2FChemical-In-Cosmetics%2Frefs%2Fheads%2Fmain%2Fchemicals-in-cosmetics-data-dictionary.xlsx&wdOrigin=BROWSELINK))
