# Customer Satisfaction & Survey Analytics

## Project Overview

This project analyzes customer survey data to evaluate satisfaction levels, identify key drivers of customer experience, and generate data-backed recommendations for improving service performance.

The analysis focuses on overall and zone-wise customer satisfaction, Net Promoter Score (NPS), relationships between satisfaction parameters, and statistical testing to identify meaningful patterns in customer feedback.

## Business Problem

The objective of the analysis is to answer:

* How satisfied are customers overall?
* How does customer satisfaction vary across zones?
* What is the overall NPS?
* Which satisfaction factors are most strongly associated with overall satisfaction?
* Are there statistically significant differences in satisfaction?
* What areas should the business prioritize for improvement?

## Dataset

The dataset contains survey responses from approximately 200 customers.

Key information includes customer/zone details and multiple customer satisfaction parameters.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Google Colab

## Analysis Workflow

1. Data loading and inspection
2. Data cleaning and validation
3. Exploratory Data Analysis (EDA)
4. Overall satisfaction analysis
5. Zone-wise satisfaction analysis
6. NPS calculation
7. Correlation analysis
8. Hypothesis testing using t-tests
9. Interpretation of findings
10. Business recommendations

## Key Analysis

### Customer Satisfaction

Calculated overall and zone-wise satisfaction scores to identify differences in customer experience across regions.

### Net Promoter Score

Calculated NPS to understand customer loyalty and willingness to recommend the service.

### Correlation Analysis

Examined relationships between individual satisfaction parameters and overall customer satisfaction to identify potential drivers of customer experience.

### Hypothesis Testing

Used t-tests to evaluate whether observed differences in satisfaction were statistically significant rather than simply due to random variation.

## Key Insights

* Overall customer satisfaction was **7.91/10**, with **81%** of customers scoring 8 or 9.
* Overall NPS was **+39.5**, with South performing best at **+61.5**.
* **Overall Loan Experience** had the strongest relationship with satisfaction (r = 0.70).
* **Welcome Letter delivery** was the lowest-rated parameter (7.76) and had the highest variability.
* **North zone** had the lowest satisfaction (7.60) and highest detractor rate (19.1%).

## Key Recommendations

* Improve the end-to-end loan experience by identifying process bottlenecks.
* Improve and monitor Welcome Letter delivery timelines.
* Investigate the reasons behind lower satisfaction in the North zone.
* Study South zone practices to identify approaches that could be applied elsewhere.
* Conduct further research to understand passive customers and improve their experience.


