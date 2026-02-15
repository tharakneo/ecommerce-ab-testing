# E-Commerce A/B Test: Product Page Conversion Analysis

## Overview
An e-commerce company developed a new product landing page to improve purchase conversion rates. This project analyzes an A/B test with 290K+ user sessions to determine whether the new page should be launched.

## Key Findings
- **Control (Old Page):** 12.04% conversion rate
- **Treatment (New Page):** 11.88% conversion rate
- **P-Value:** 0.19 — not statistically significant
- **Recommendation:** Do not launch the new page

## Methodology
- Data cleaning and validation (removed 3,894 duplicates and mismatched assignments)
- Power analysis and sample size calculation
- Two-proportion Z-test with 95% confidence intervals
- Country-level segmentation analysis (US, UK, Canada)
- Logistic regression controlling for country effects
- Business recommendation with actionable next steps

## Tools & Libraries
Python, Pandas, NumPy, SciPy, Statsmodels, Matplotlib, Seaborn

## Dataset
[Kaggle: E-Commerce A/B Testing](https://www.kaggle.com/datasets/ahmedmohameddawoud/ecommerce-ab-testing)

## How to Run
1. Open the notebook in Google Colab or Jupyter
2. Upload `ab_test.csv` and `countries_ab.csv` to the working directory
3. Run all cells sequentially
