# Employee KPI's

## Objective

Analyze employee compensation, performance, and experience data to identify department-level patterns and relationships between key workforce metrics that can inform staffing and compensation decisions.

## Dataset

The dataset (`employees.csv`) contains individual employee records, including department affiliation, salary, years of experience, and performance scores. Each row represents a single employee.

## Tools Used

* **Language:** R
* **Libraries:** tidyverse, ggplot2, ggrepel, viridis
* **Techniques:** exploratory data analysis, aggregation, correlation analysis, data visualization

## Key Questions

* How do average salary and performance scores vary across departments?
* Is there a relationship between years of experience and salary?
* Which departments differ most from organization-wide compensation and performance trends?
* Are there notable outliers that may indicate exceptional cases or data quality issues?

## Key Findings

* Average salary varies meaningfully across departments, indicating potential structural differences in compensation
* Average performance scores are not uniform across departments, suggesting differences in team outcomes or evaluation standards
* Years of experience show a positive correlation with salary, though variability indicates experience alone does not fully explain compensation
* One or more employees appear as outliers in experience–salary space, warranting further review

## Data Cleaning & Assumptions

* Missing values were excluded from calculations using complete-case analysis
* Department-level averages assume employees within departments are comparable
* Linear trend lines summarize relationships but do not imply causation
* Outliers were flagged for interpretation rather than removed

## How to Run

1. Clone the repository
2. Open the R script or RMarkdown file
3. Ensure required packages are installed
4. Run the script to reproduce analysis and figures

## Next Steps

* Incorporate additional variables such as role level or tenure
* Perform statistical testing to compare departments formally
* Extend analysis into an interactive dashboard for stakeholders

