---
editor_options: 
  markdown: 
    wrap: 72
---

# Executive Summary: Employee Attrition Analysis

**Project Author:** Spencer Thompson
([thompsonsm\@smu.edu](mailto:thompsonsm@smu.edu){.email})\
**Date:** October 21, 2025 ---

## Project Overview

This analysis examines employee attrition patterns within the
organization to identify key predictive factors and develop
cost-effective intervention strategies. The study analyzed 870
employees, of which 140 (16.1%) experienced attrition.

## Methodology

**Predictive Modeling:** Three machine learning models were developed
and compared: - Logistic Regression - K-Nearest Neighbors (KNN) - Naive
Bayes

## Key Findings

### Primary Attrition Predictors

The logistic regression model identified 16 statistically significant
predictors of employee attrition, with the top five being:

1.  **Overtime** (z = 7.499) - Most significant predictor
2.  **Job Involvement** (z = -5.046)
3.  **Job Satisfaction** (z = -4.554)
4.  **Number of Companies Worked** (z = 4.234)
5.  **Years Since Last Promotion** (z = 4.037)

Additional significant factors include business travel frequency,
commute distance, job role (directors show lower attrition), work-life
balance, and training frequency.

### Statistical Test Results

-   **Distance from Home:** Attrited employees traveled significantly
    farther to work (0.35-3.5 miles more on average, 95% CI)
-   **Job Satisfaction vs. Overtime:** No significant difference found
    between overtime and non-overtime employees
-   **Work-Life Balance:** No significant differences across travel
    frequency levels
-   **Relationship Satisfaction:** Marginal significance (p = 0.09)
    across marital status groups

## Model Performance Comparison

| Model                   | Accuracy | Sensitivity | Specificity | Total Cost      |
|-------------------------|----------|-------------|-------------|-----------------|
| **Logistic Regression** | 88.2%    | 46.9%       | 97.6%       | \$2,402,552     |
| **K-Nearest Neighbors** | 81.9%    | 4.0%        | 100%        | \$4,296,976     |
| **Naive Bayes**         | 65.1%    | 71.4%       | 63.7%       | **\$1,398,482** |

**Model Interpretation:** - **Logistic Regression:** Best overall
accuracy and balanced performance; ideal when intervention and
replacement costs are similar - **KNN:** Minimizes false positives (100%
specificity); suitable when intervention costs are high - **Naive
Bayes:** Highest sensitivity for detecting actual attrition risk; lowest
total expenditure considering both intervention costs (\$200 per
employee) and replacement costs (50% of annual salary)

## Cost Analysis

Based on intervention cost of \$200 per identified at-risk employee and
replacement cost equal to 50% of annual salary:

-   **Naive Bayes** achieved the lowest total expenditure at \$1,398,482
-   This represents a **42% cost savings** compared to KNN and **40%
    savings** compared to Logistic Regression
-   The model correctly identified 71.4% of employees who would actually
    leave, allowing for proactive intervention

## Strategic Recommendations

### Immediate Actions

1.  **Address Overtime Burden**
2.  **Enhance Job Satisfaction and Involvement**
3.  **Reduce Commute and Travel Strain**
4.  **Strengthen Manager-Employee Relationships**
5.  **Foster Work-Life Balance**
6.  **Build Stronger Workplace Relationships**

## Conclusion

Employee attrition is a complex issue driven primarily by work demands
(overtime), job satisfaction, and employee engagement. The Naive Bayes
predictive model offers the most cost-effective approach to identifying
at-risk employees, with 71.4% sensitivity and the lowest total cost
impact.

By implementing the recommended interventions—particularly addressing
overtime, enhancing job satisfaction, and improving work-life
balance—the organization can proactively reduce attrition and associated
replacement costs. The financial case is compelling: early intervention
through predictive modeling can save over \$1 million compared to
reactive approaches.
