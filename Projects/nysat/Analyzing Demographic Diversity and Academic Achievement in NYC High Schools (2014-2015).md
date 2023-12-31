# Analyzing Demographic Diversity and Academic Achievement in NYC High Schools (2014-2015)

## Overview

**Research Question:** During the 2014-2015 school year, do high schools with more diverse student populations, as indicated by the racial breakdown, exhibit variations in average scores on SAT test sections compared to schools with less diverse student populations in New York City?

The focus of this research is to investigate whether there are variations in the average scores on SAT test sections among high schools in New York City during the 2014-2015 school year based on the diversity of their student populations, as indicated by the racial breakdown. This research is important for several reasons:

1. Educational Equity: Understanding the relationship between student diversity and SAT scores can shed light on potential disparities in educational opportunities and outcomes. It helps identify whether diverse schools face unique challenges or advantages in preparing students for standardized tests.

2. Policy Implications: The findings of this research can inform education policymakers and school administrators about the impact of student diversity on academic performance. It may lead to the development of strategies and policies aimed at improving equity and educational outcomes.

3. Resource Allocation: Schools with diverse student populations may require different resources and support systems. Identifying variations in SAT scores can help allocate resources effectively and tailor interventions to meet the needs of specific student groups.

4. College Readiness: SAT scores are often used as a predictor of college readiness. Understanding how diversity influences these scores can provide insights into the preparedness of students from different racial backgrounds for higher education.

5. Social and Cultural Understanding: Beyond academics, the research can contribute to a deeper understanding of the social and cultural dynamics within schools. It may highlight the role of diversity in fostering a more inclusive and enriched learning environment.



## Table of Contents
- [Data Sources](#data-sources)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Key Results](#key-results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Data Sources

### [scores.csv](https://www.kaggle.com/datasets/nycopendata/high-schools)
The "scores.csv" file contains detailed information about various schools, focusing on their demographic makeup and academic performance in terms of SAT scores. Here's a brief summary of its key aspects:

1. **Basic School Information**: 
   - Includes data like 'School ID', 'School Name', 'Borough', 'Building Code', 'Street Address', 'City', 'State', and 'Zip Code'.

2. **Geographical Data**: 
   - Contains 'Latitude' and 'Longitude' for each school.

3. **School Operation Details**:
   - Information like 'Phone Number', 'Start Time', and 'End Time' of the school day.

4. **Student Demographics**:
   - Demographic breakdown in percentages, such as 'Percent White', 'Percent Black', 'Percent Hispanic', and 'Percent Asian'.

5. **Enrollment and Testing Data**:
   - Includes 'Student Enrollment' numbers and 'Percent Tested', indicating the proportion of students who took the SAT.

6. **SAT Performance**:
   - Academic performance data, with average scores for 'SAT Math', 'SAT Reading', and 'SAT Writing'.

## Technologies Used

* **Programming Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Data Visualization:** Tableau
* **Tools:** Jupyter Notebooks, Git

## Project Structure

- **Notebooks:** [https://github.com/jamiekawilkinson/jupyternotebooks]
  - Exploring Demographic Diversity and Academic Achievement.ipynb
  - nysat_cleaning.ipynb

- **Data:** [https://github.com/jamiekawilkinson/datasets]
  - `scores.csv`
  - `nyscores_clean.csv`           

## Key Results

* From these results, it appears that schools with higher diversity (as measured by the diversity index) tend to have higher average SAT scores in all three sections (Math, Reading, Writing) compared to schools with lower diversity.
This analysis provides an interesting insight into the relationship between student population diversity and academic performance as measured by SAT scores. Keep in mind, however, that correlation does not imply causation, and many other factors could influence these results.¶
