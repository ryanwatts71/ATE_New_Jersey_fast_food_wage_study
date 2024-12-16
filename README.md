# ATE_New_Jersey_fast_food_wage_study
This repository contains the R code for Problem 3 of Exam 3, where panel data was analyzed to evaluate the impact of New Jersey’s minimum wage increase in 1992 on employment in the fast-food industry.

Performed Analysis

Data Preparation: The provided dataset, "ECON 418 518 Exam 3 Data.csv," was loaded into R as a data.table for processing and analysis.

Difference-in-Difference (DiD) Analysis: A DiD model was used to estimate the causal effect of the minimum wage increase. The analysis included state and time-period indicators, along with their interaction term to isolate the treatment effect.

Descriptive Statistics: Mean employment levels were calculated for each state and time period to establish baseline differences and trends.

Effect Estimation: The Average Treatment Effect (ATE) was computed using the DiD formula, supplemented by visual representations of the results.

Confidence Interval Construction: A 95% confidence interval was manually calculated and verified using R. Hypothesis tests were performed to assess the significance of the estimated treatment effect.

Fixed Effects Model: Restaurant fixed effects were added to the DiD model to control for unobserved heterogeneity, and the results were compared to the initial estimates.

Findings

The DiD analysis showed a significant effect of the minimum wage increase on employment in New Jersey’s fast-food industry relative to Pennsylvania.

The inclusion of restaurant fixed effects slightly adjusted the estimates but did not alter the overall conclusions.

Hypothesis tests confirmed that the treatment effect was significantly different from zero, supporting the causal interpretation of the results.

Potential limitations were noted, including the possibility of low statistical power and time-variant confounders.
