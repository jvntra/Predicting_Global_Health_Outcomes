Jean-Paul Ventura

# Investigation of Life Expectancy using Multiple Linear Regression:

### Question considered:

To what extent to different health factors have an effect on observed life expectancy worldwide?

## Context

This investigation was undertaken to explore the dependence of life expectancy measured for years between 2000 and 2015. on several immunological, mortality, economic and social factors in order to inform prescriptive measures of
public and global health.

## Content

1.) Data:
The data-set containts information on life expectancy and other factors for 193 countries has been prepared from the WHO data repository website with corresponding economic data sourced from United Nations data.

2.) Data Cleaning process and Preliminary Data Exploration notebook: 'prelim_data_exploration.ipynb'

3.) Final notebook: 'GlobalHealthOutcomes_final.ipynb' compilation of results.



## Process

This project was undertaken following the Cross-Industry Standard Process for Data Mining (CRISP-DM) methodology to establish data and case understanding. Recursive methodologies were employed, including developing statistical insights and measures in order to produce a more appropriate dataset for multiple linear regression modeling. 

These methods included: 

- Estimating outliers using the *Tukey statistical method*
- Handling outliers via the winsorization technique.
- Inspecting the pearson correlation among explanatory variables themselves, between those variables and the target: life expectancy.
- - feature selection based on high correlation coefficients
- - feature engineering of categorical variable.



