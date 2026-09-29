# Hearing Health Behavior Analysis & "Hearwell" Product Validation

Exploratory analysis and hypothesis testing of a hearing-wellness survey (N=382, majority Gen Z) to validate market demand and feature priorities for **Hearwell**, a proposed hearing-health mobile app. The project moves beyond descriptive reporting into diagnostic analytics using statistical hypothesis testing to validate (or disprove) product assumptions before development resources are committed.

## Objective

Determine whether headphone usage habits pose real risks to hearing/social wellbeing, identify the true barrier to hearing-test adoption, and validate which app features and pricing model the target market actually wants to guide a data-backed Go-to-Market strategy.

## Methodology & Tools

- **Data Processing:** Python (Pandas)  cleaning nulls and outliers in age/usage fields
- **Statistical Testing:** SciPy  Chi-Square test of independence to measure significance between behavioral variables
- **Visualization:** Seaborn & Matplotlib  demographic breakdowns, correlation heatmaps, Willingness-to-Pay (WTP) segmentation

## Key Insights

**1. Physical discomfort, not social withdrawal, is the real issue**
Chi-Square testing found a statistically significant relationship between headphone usage duration and physical ear discomfort (p = 0.009), but no significant relationship between usage duration and missing important sounds or feeling socially isolated (p = 0.551). This disproves the common assumption that heavy headphone use itself erodes public awareness the real issue is physical tolerance, not attentional/social harm.

**2. The barrier to hearing tests is awareness, not cost**
234 respondents cited lack of awareness as their main reason for never taking a hearing test far ahead of cost or stigma. This means user acquisition should prioritize education campaigns over discounting or price competition.

**3. Gen Z wants practicality over medical depth**
Despite being a health app, the most-requested features were Quick Tests and gamified interactions rather than heavy medical integrations. With Gen Z respondents dominating the sample (287 of 382), gamification is a retention requirement, not a nice-to-have.

**4. Awareness converts to willingness to pay**
195 respondents chose "Maybe, if it offers good value" for a paid app — a pragmatic, not resistant, market. Crosstab analysis further showed that respondents with higher hearing-health awareness were substantially more likely to be willing to pay, confirming that education directly drives monetization potential.

## Analytical Value

This project demonstrates the shift from descriptive metrics reporting to diagnostic, decision-ready analytics — using formal hypothesis testing to validate or reject product and market assumptions, helping ensure development resources are not spent on the wrong features or a flawed go-to-market approach.

## Tech Stack

`Python` `Pandas` `SciPy` `Seaborn` `Matplotlib` `Google Colab`

---
*Individual project. Dataset: Kaggle , N=382 respondents.*
