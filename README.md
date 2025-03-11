# Gapminder Dataset Analysis

## Project Overview
This project involves analyzing the [Gapminder Dataset](https://www.kaggle.com/datasets/albertovidalrod/gapminder-dataset) to study data analysis concepts and apply statistical techniques.

## Activities Performed

### 1. Initial Dataset Analysis
- Exploratory analysis of dataset characteristics (size, features, missing values).

### 2. Unconditional Mono-variate Analysis
For each predictor variable:
- Generated histograms and box plots using all observations (excluding NaN values)
- *Note: Missing values were excluded from the analysis*

### 3. Class-Conditional Mono-variate Analysis
For each predictor variable across different classes:
- Plotted comparative histograms
- Created summary tables with the following statistics:
  
  | Statistic    | Symbol | Formula Representation |
  |--------------|--------|-------------------------|
  | Mean         | μ      | `μ = (Σx)/n`            |
  | Standard Deviation | σ | `σ = √(Σ(x-μ)²/n)` |
  | Skewness     | γ      | `γ = (Σ(x-μ)³/n)/σ³`    |

## Implementation Details
- **Tools Used**: Python (Pandas, Matplotlib, Seaborn)
- **Dataset Version**: Gapminder 2023 from Kaggle
- **Key Files**: 
  - `data_analysis.ipynb` (Jupyter notebook with full analysis)
  - `visualizations/` (directory containing generated plots)

---

*Note: All statistical calculations were performed after handling missing values appropriately.*
