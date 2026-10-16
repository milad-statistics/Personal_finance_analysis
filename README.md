# Personal Finance Analysis

## Project Overview

This project explores a synthetic personal finance dataset using Python. The analysis focuses on spending patterns across categories and savings behavior, using descriptive statistics, visualizations, and correlation analysis.

## Dataset

- **Dataset:** [Personal Finance Tracker Dataset](https://www.kaggle.com/datasets/khushikyad001/personal-finance-tracker-dataset)
- **Source:** Kaggle
- **Data type:** Synthetic / simulated data, as described by the dataset publisher.

The dataset includes fields related to income, expenses, savings, financial stress, spending categories, and savings-goal achievement.

## Objectives and Questions

### 1. Spending Patterns by Category

1. Which categories have the highest and lowest total monthly expenses?
2. What is the average monthly expense for each category, and which categories have the highest and lowest averages?
3. What percentage of total monthly expenses is discretionary spending?
4. What percentage of total monthly expenses is essential spending?
5. Does average monthly expense differ across income types?

### 2. Savings Behavior Analysis

6. What are the mean and median savings rates, and how are they distributed?
7. What percentage of records indicate that the savings goal was met?
8. Is there a relationship between savings rate and achieving the savings goal?
9. Does average savings rate differ across financial stress levels?
10. Is there a relationship between monthly income and actual savings?

## Tools and Libraries

- **Python** — data analysis and processing
- **Pandas** — data loading, cleaning, grouping, and summary statistics
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical plots and distribution visualization
- **Jupyter Notebook** — documenting and running the analysis

## Workflow

1. Loaded the dataset into a Pandas DataFrame.
2. Inspected the dataset structure and data types.
3. Checked for missing values and duplicate rows.
4. Converted the `Date` column to a datetime data type.
5. Used grouping, aggregation, percentages, descriptive statistics, visualizations, and correlation analysis to answer the project questions.

## Key Findings

### Spending Patterns

- **Highest total monthly expenses by category:** Insurance.
- **Lowest total monthly expenses by category:** Rent.
- **Highest average monthly expense by category:** Groceries.
- **Lowest average monthly expense by category:** Rent.
- **Discretionary spending:** Approximately **16.62%** of total monthly expenses.
- **Essential spending:** Approximately **73.56%** of total monthly expenses.
- Average monthly expenses were similar across the reported income types:
  - Salary: approximately **3,022**
  - Mixed: approximately **2,989**
  - Freelance: approximately **2,980**

### Savings Behavior

- **Mean savings rate:** Approximately **22%**.
- **Median savings rate:** Approximately **23%**.
- **Savings goal achieved:** Approximately **9.23%** of records.
- The Pearson correlation between savings rate and savings-goal achievement was approximately **-0.01** (*p* = 0.46), indicating virtually no observed linear association in this dataset.
- Average savings rates by financial stress level were close:
  - High: approximately **23%**
  - Medium: approximately **22%**
  - Low: approximately **22%**
- Monthly income and actual savings showed a positive association, with both Pearson and Spearman correlation coefficients reported at approximately **0.74**.

## Conclusion

In this dataset, spending summaries varied by category, while average expenses across income types and average savings rates across financial stress levels were relatively similar. Savings-goal achievement was recorded in a small proportion of rows. Monthly income showed a fairly strong positive association with actual savings, whereas savings rate showed virtually no linear association with the binary savings-goal indicator.

These findings describe only the dataset analyzed and should not be interpreted as evidence about all individuals' real-world financial behavior. Correlation does not establish causation, and the dataset is described by its publisher as synthetic.

## Project File

The analysis is documented in the Jupyter Notebook:

- `personal_finance_analysis.ipynb`

## How to Run

1. Download or clone this project.
2. Ensure Python and Jupyter Notebook are installed.
3. Install the required libraries if necessary:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open `personal_finance_analysis.ipynb` in Jupyter Notebook or Visual Studio Code.
5. Run the notebook cells from top to bottom.

## Author's Note

This project was created as a data analysis practice project to apply Python-based data cleaning, exploratory analysis, visualization, and statistical techniques.
