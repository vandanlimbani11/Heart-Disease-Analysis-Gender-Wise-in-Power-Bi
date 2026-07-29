# Heart-Disease-Analysis-Gender-Wise-in-Power-Bi
❤️ Heart Disease Analysis — Gender-Wise
Interactive Healthcare Analytics Dashboard Built with Power BI
An interactive Power BI project that explores heart-failure survival outcomes across gender and age groups while examining important clinical indicators such as serum sodium, ejection fraction, diabetes, high blood pressure, and hypertension.

📌 Project Overview

This project presents a gender-wise analysis of heart-disease patient outcomes using Microsoft Power BI. The dashboard makes it possible to switch between female and male patients and immediately compare survival rate, average survival age, total survivors, total deaths, age-group distribution, and clinical risk factors.

The report is designed to answer an important analytical question:

How do survival outcomes and major clinical indicators vary across gender and age groups?

🎯 Project Objectives

Measure the overall survival and mortality rates.

Compare patient outcomes by gender.

Identify the age groups with the highest and lowest survival counts.

Analyze average serum-sodium levels across age groups.

Compare ejection fraction across age groups.

Examine the distribution of diabetes, high blood pressure, and hypertension.

Create an interactive report that supports gender-based filtering.

Present complex healthcare information in a clear and accessible format.

📊 Dashboard Preview

Overall Heart Disease Analysis



Male Patient Analysis



Select the Female or Male button in Power BI to update every KPI and chart for the chosen gender.

📈 Key Performance Indicators

Overall Patient Population

KPI

Value

Total patients

299

Total survivors

203

Total deaths

96

Survival rate

67.89%

Mortality rate

32.11%

Average survival age

58.76 years

Male Patients

KPI

Value

Total male patients

194

Male survivors

132

Male deaths

62

Male survival rate

68.04%

Male mortality rate

31.96%

Average male survival age

58.83 years

<details>
<summary><strong>How the percentages were interpreted</strong></summary>

The overall patient total was calculated from 203 survivors and 96 deaths:

Total patients = 203 + 96 = 299
Survival rate = 203 ÷ 299 × 100 = 67.89%
Mortality rate = 96 ÷ 299 × 100 = 32.11%

The male patient total was calculated from 132 survivors and 62 deaths:

Total male patients = 132 + 62 = 194
Male survival rate = 132 ÷ 194 × 100 = 68.04%
Male mortality rate = 62 ÷ 194 × 100 = 31.96%

</details>

🧩 Dashboard Components

1. Gender Filter

Custom female and male buttons allow users to analyze the dashboard gender-wise. The filter updates all KPI cards and visualizations simultaneously.

2. KPI Cards

The report contains four headline metrics:

Survival rate

Average survival age

Total survivors

Total deaths

3. Survival Count and Serum Sodium

A combination chart compares:

Survival count by age group

Average serum-sodium level by age group

4. Survival Count and Ejection Fraction

This visual compares patient counts with average ejection fraction for each age group.

5. Survival Trend by Age Group

An area chart shows how the number of survivors is distributed across:

Below 40

40–50

51–60

61–70

71+

6. Clinical Risk-Factor Analysis

A ribbon-style visual compares the presence of:

Diabetes

High blood pressure

Hypertension

across the different age groups.

🔍 Age-Group Findings

Overall survival distribution

Age group

Survival count

51–60

63

61–70

63

40–50

48

71+

21

Below 40

8

Male survival distribution

Age group

Male survival count

51–60

46

61–70

37

40–50

28

71+

16

Below 40

5

💡 Key Insights

Overall survival
203 of 299 patients survived, producing a 67.89% survival rate.
Approximately two-thirds of the patient population survived.

Male survival
132 of 194 male patients survived, producing a 68.04% survival rate.
The male survival rate is very close to the overall rate.

Age concentration
The 51–60 and 61–70 groups each contain 63 overall survivors.
Most surviving patients in the dataset are concentrated between ages 51 and 70.

Younger patients
The Below-40 group has the smallest survival count.
This reflects the smaller number of younger patients represented in the dataset and should not alone be treated as a lower survival probability.

Serum sodium
Average values stay close to 137 across age groups.
Serum sodium appears relatively stable at the aggregate age-group level.

Ejection fraction
Average ejection fraction varies across age groups.
The 71+ group shows a comparatively higher average in the overall dashboard, while the Below-40 group is lower.

🛠️ Tools and Skills Used

Tool/Skill

Application

Microsoft Power BI

Interactive dashboard development

Power Query

Data cleaning and transformation

DAX

Survival, mortality, total, and average measures

Data modelling

Connecting fields and measures

Data visualization

KPI cards, combination charts, area charts, and ribbon charts

Slicers and bookmarks

Gender-wise dashboard interaction

Healthcare analytics

Interpretation of patient and clinical variables
