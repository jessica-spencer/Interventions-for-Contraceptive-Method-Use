# Increasing Contraceptive Choice: Exploring Opportunities and Health Impacts in Indonesia

## Background and Significance

Contraceptives are far more than a method of preventing pregnancy—they represent a transformative tool for health and life opportunities for individuals capable of pregnancy. The broader implications of contraceptive access extend across multiple critical domains:

### Health Impacts
Epidemiological evidence from the United States demonstrates significant health benefits:

  - Improved pregnancy spacing reduces risks of premature births and low birth weight
  - Enables management of complex health conditions such as diabetes and heart disease
  - Supports mental health and overall well-being, i.e.,  decreases risk of depression

### Socioeconomic Opportunities
Contraceptive choice is a powerful lever for individual empowerment:

- Enables women to pursue advanced education
- Supports career development and professional growth
- Enhances family planning and economic stability

Notably, each dollar invested in family planning generates $7 in healthcare cost savings, highlighting the broader societal impact.

## Research Context

While these insights are drawn from U.S. data, they provide a robust theoretical framework for investigating contraceptive use in the Indonesian context.

## Research Overview

### Data Source
**1987 National Indonesia Contraceptive Prevalence Survey** (linked below)

### Primary Research Question
*What interventions can effectively increase contraceptive method utilization among women in this population?*

### Methodological Approach
Multiple logistic regression analysis

### Key Finding
Education emerges as a critical intervention for increasing contraceptive use among women in this population.

## Report Structure

0. Dataset Explanation
1. Exploratory Data Analysis
   - Variable Selection and Investigation
2. Relative Odds of Contraceptive Methods
3. Modeling and Predictive Strength of Independent Variables
4. Conclusions and Recommendations


[Learn more about the benefits of contraceptive choice](https://www.guttmacher.org/gpr/2017/11/why-family-planning-policy-and-practice-must-guarantee-true-choice-contraceptive-methods)

---


## Possible Extensions:

consider including mutual information for variable selection.  I would love to produce a mutual information heatmap to choose elements to consider in this regression. My version of R does not support tidyinftheo, which can create the map. 

Why? Mutual information is a bit more complex than correlation. It measures how much knowing the value of one variable reduces uncertainty about the value of the other. In other words, it tells us how much information about one variable is contained in the other. Mutual information values are always non-negative, with larger values indicating a stronger relationship.
