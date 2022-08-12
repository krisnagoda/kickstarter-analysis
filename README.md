# Kickstarting with Excel

## Overview of Project

Understand how other campaigns performed based on launch date and goal. 

### Purpose
Use data to drive insight into prior campaign outcomes to increase campaign success. 

### Analysis of Outcomes Based on Launch Date

Pivot table in worksheet labeled "Theater Outcomes by Launch Date":

![Parent Category Outcomes.png](https://github.com/krisnagoda/kickstarter-analysis/blob/5546f68f30a49dd57dfb42bc90d6f2a46d5f20b5/Theater_Outcomes_vs_Launch_Pivot.png)

Line chart showing number of successful, failed, or canceled projects by month:

![Parent Category Outcomes.png](https://github.com/krisnagoda/kickstarter-analysis/blob/5546f68f30a49dd57dfb42bc90d6f2a46d5f20b5/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

Data table in worksheet labeled "Outcome Based Goals":

![Outcome_Based_Goals_Data.png](https://github.com/krisnagoda/kickstarter-analysis/blob/29b5752e4fde6296e7323598f8e077c21c1e4b48/Outcome_Based_Goals_Data.png)

Line chart showing goal-amount ranges on the xaxis and percentage of successful, failed, or canceled projects on the yaxis:

![Outcomes_vs_Goals.png](https://github.com/krisnagoda/kickstarter-analysis/blob/8e5ae125d74f39fcc1b0dd17e29e47116d9653c6/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

This analysis required unix date conversion, many functions (like IF, COUNTIFS and ROUND), some simple equations and pivot tables. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1. The month of July nets the highest total successful theater outcomes.
  2. September, October, November and December have the smallest gap between successful and failed theater outcomes.

- What can you conclude about the Outcomes based on Goals?

  1. The sweet spots, or range in this case, for a successful outcome is less than $1,000 – $5,000 and $35,000 - $40,000.
  2. With successful and failed outcomes when one goes up, the other goes down because we had zero canceled outcomes.

- What are some limitations of this dataset?

  1. Other data related to what might make one campaign more successful than another. For example, what if a specific playwright had a fan base that could support a larger goal?

- What are some other possible tables and/or graphs that we could create?

  1. This dataset could provide many other cuts specifically related to category and sub category.
