# The-Relationship-Between-EURIBOR-Inflation-and-Unemployment-Rate-with-Python
  The project is analyzing the behavior of EURIBOR and try to estimate it using macroeconomics variables. The goal is to explain and predict EURIBOR based on macroeconomic drivers, which are inflation (by using HICP index) and unemployment rate. The analysis period is 2015-2024 to see the difference before, during, and after COVID period.
# About
  This project analyzes the behavior of EURIBOR and tries to estimate it using macroeconomic variables. The goal is to explain and predict short-term interest rates (EURIBOR) based on macroeconomic drivers:
  - **Inflation** (measured using HICP index)
  - **Unemployment rate**
The analysis period is **2015–2024** to compare 3 period of time:
  - Pre-COVID period
  - COVID period
  - Post-COVID/high inflation period

# Objectives
  - Describe how EURIBOR moves over time.
  - Analyze how EURIBOR reacts to inflation shocks and labor market conditions.
  - Build a simple predictive model using Python.

Key Questions:
  📈 Does high inflation and low unemployment affect EURIBOR to go up?
  📉 What happens when inflation is low and unemployment is high?

# Data & Sources
  [EURIBOR rates](https://www.euribor-rates.eu/en/)
  [HICP (inflation index, also used as proxy in the EU](https://ec.europa.eu/eurostat/databrowser/view/prc_hicp_midx__custom_18622429/default/table)
  [Unemployment rate (labor market indicator)](https://ec.europa.eu/eurostat/databrowser/view/ei_lmhr_m__custom_18622722/default/table)

  All data is treated as time series and aligned by month.
  Time horizon: **Jan 2015 → 2024** to capture:
  1. Negative/zero-rate environment
  2. COVID shock
  3. ECB moves on those periods
# Methodology
**1. Data cleaning & preprocessing
**

  - Importing macroeconomic series into Python
  - Merging into one dataframe by date

**2. Exploratory analysis, Normality Test, & Hypothesis Testing
**

  - Trend plots of EURIBOR, inflation, and unemployment
  - Visual comparison before/during/after COVID

**3. Regression/modelling (Multiple Regression & Random Forest)
**
  - Use inflation and unemployment as independent variables
  - Try to explain EURIBOR level as the dependent variable
  - Evaluate how strong each driver is

**4. Interpretation
**
  - Intepret the movements in EURIBOR to macroeconomics conditions
# Repository structure
  data/ Raw/cleaned macroeconomic data (EURIBOR, HICP, and unemployment)
  notebooks/ Jupyter notebook with:
  - preprocessing
  - visualizations
  - regression/prediction
  README.md Project description (this file)

# Summary/Why it matters
  EURIBOR is strongly influenced by:
  - **inflation pressure** (high inflation → central bank reacts → higher rates)
  - **labor market strength** (low unemployment → economy recovery → higher rates)

  By looking at **2015–2024**, we can see:
  - Before COVID: rates extremely low despite weak inflation
  - During COVID: emergency policy
  - After COVID: inflation spike & unemployment relatively controlled causing EURIBOR to jump
  This project shows how macro variables can be used to understand and forecast interest rate behavior in Europe using Python.

# Author
  Celia Aviana
  Nguyen Minh Anh
  Dang Anh Minh
  Nour El Houda Harzallah
  Thanatip Trisurat
  MSc International Finance (Rennes School of Business)
  Focus: Financial markets, macroeconomics, and data analysis with Python
