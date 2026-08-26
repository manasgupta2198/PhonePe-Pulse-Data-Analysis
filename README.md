# 📱 PhonePe Digital Payments Case Study

Python-based exploratory data analysis of the **PhonePe Pulse** dataset, focused on transaction trends, transaction types, device usage, registered users, and district-level demographic patterns across India.

## 🎯 Project Objective

The objective of this case study is to load, clean, explore, and analyze PhonePe transaction and demographic data to derive meaningful business insights and visualizations.

The analysis covers:

- Transaction trends across years, quarters, and states
- Transaction amount and transaction volume analysis
- Most common transaction types by state and quarter
- Device-brand usage and registered-user distribution
- District-level population and demographic analysis
- Missing-value and data-quality checks
- State and district comparisons

## 📊 Datasets Used

The case study uses five datasets:

1. **State_Txn and Users** — state-level transactions, transaction amount, ATV, registered users, and app opens
2. **State_TxnSplit** — state-level transaction types, transaction counts, amounts, and ATV
3. **State_DeviceData** — device brands, registered users, and brand percentages at the state level
4. **District_Txn and Users** — district-level transactions, transaction amount, ATV, registered users, and app opens
5. **District Demographics** — district population, area, density, headquarters, code, and alternate name

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** — data loading, cleaning, grouping, aggregation, and analysis
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Jupyter Notebook / Google Colab** — analysis environment
- **Excel** — source dataset

## 🔎 Case Study Analysis

### Task 1 — Data Loading & Understanding

- Display first, last, middle, and every 10th row as required
- Review summary statistics for numerical columns
- Check data types for each column
- Identify missing values
- Calculate missing-value percentages
- Identify columns with the highest missing-value percentage
- Calculate total states and total districts
- Identify the state with the highest number of districts

### Task 2 — Exploratory Data Analysis

#### Transaction Trends
- Calculate total transaction volume and transaction amount for each state over the years
- Identify the top 5 states with the highest transaction volumes
- Identify the bottom 5 states with the lowest transaction volumes

#### Transaction Type Analysis
- Determine the most frequent transaction type for each state and quarter

#### Device Analysis
- Identify the device brand with the highest number of registered users in each state

#### District Population Analysis
- Identify the highest-population district for every state
- Create a column chart showing the highest-population district for each state

## 📈 Key Business Questions

1. How does PhonePe transaction activity change over time?
2. Which states have the highest and lowest transaction volumes?
3. Which transaction types are most common across states and quarters?
4. Which device brands have the strongest registered-user presence in each state?
5. Which districts have the highest populations within their respective states?
6. What data-quality issues need to be addressed before analysis?

## 💡 Business Value

The analysis helps understand digital-payment adoption across Indian states and districts. It can highlight high-growth regions, transaction patterns, device preferences, and population-related differences that may support business and market-expansion decisions.

## 📂 Repository Contents

| File | Description |
|---|---|
| `phonepay_pulse_data_analysis.ipynb` | Python notebook containing the analysis and visualizations |
| `phonepe-pulse_raw-data_q12018-to-q22021-v0-1-5-1720351752 (1).xlsx` | Source PhonePe Pulse dataset |
| `README.md` | Project documentation |

## ▶️ How to Run

1. Download or clone this repository.
2. Open `phonepay_pulse_data_analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
3. Keep the Excel dataset available in the working directory expected by the notebook.
4. Run the notebook cells from top to bottom.
5. Review the tables, visualizations, and analytical observations.

## 📌 Project Structure

```text
PhonePe-Pulse-Data-Analysis/
│
├── phonepay_pulse_data_analysis.ipynb
├── phonepe-pulse_raw-data_q12018-to-q22021-v0-1-5-1720351752 (1).xlsx
└── README.md
```

## 🚀 Skills Demonstrated

**Python | Pandas | NumPy | Matplotlib | Data Cleaning | Exploratory Data Analysis | Data Visualization | GroupBy | Aggregation | Missing-Value Analysis | Business Insights**

## 👤 Author

**Manas Gupta**  
Aspiring Data Analyst | Python | SQL | Excel | Power BI
