# DS4002_Case_Study_Fertility_Time_Series

## Hook and Rubric
The hook document describing the case study is titled HookDocument.pdf and is located in the main part of the repository. Similarly, the rubric document is titled Rubric.pdf and is located in the main part of the repository. The rubric document outlines formatting details, final deliverables and submission requirements, and tips on how to approach this case study. 

## Data
The required raw datasets for this study are:
1. GDP_per_capita_current_USD.csv
2. homicides_per_100000.csv
3. womens_educational_attainment.csv
4. fertility_rate.csv
5. UN_fertility_projections.csv
6. infant_mortality.csv
7. life-expectancy.csv
They can all be found in the DATA folder. 

<details>
<summary>The corresponding references for the datasets are listed as needed.</summary>
<br>

  1. Data compiled from multiple sources by World Bank (2025) – with minor processing by Our World in Data. “GDP per capita – World Bank – In constant international-$” [dataset]. Data compiled from multiple sources by World Bank, “World Development Indicators” [original data]. Retrieved March 5, 2025 from https://ourworldindata.org/grapher/gdp-per-capita-worldbank
  2. IHME, Global Burden of Disease (2024) – with minor processing by Our World in Data. “Homicide rate” [dataset]. IHME, Global Burden of Disease, “Global Burden of Disease - Deaths and DALYs” [original data]. Retrieved March 5, 2025 from https://ourworldindata.org/grapher/homicide-rate
  3. Barro and Lee (2015); Lee and Lee (2016) – with major processing by Our World in Data. “Average years of schooling (women aged 15–64)” [dataset]. Barro and Lee, “Projections of Educational Attainment”; Lee and Lee, “Human Capital in the Long Run” [original data].
  4. UN, World Population Prospects (2024) – processed by Our World in Data. “Fertility rate, total – UN WPP” [dataset]. United Nations, “World Population Prospects” [original data].
  5. UN, World Population Prospects (2024) – processed by Our World in Data. “Fertility rate, medium projection – UN WPP” [dataset]. United Nations, “World Population Prospects” [original data].
  6. United Nations Inter-agency Group for Child Mortality Estimation (2024) – with major processing by Our World in Data. “Infant mortality rate” [dataset]. United Nations Inter-agency Group for Child Mortality Estimation, “United Nations Inter-agency Group for Child Mortality Estimation”; Various sources, “Population” [original data]. Retrieved March 5, 2025 from https://ourworldindata.org/grapher/infant-mortality
  7. UN WPP (2024); HMD (2024); Zijdeman et al. (2015); Riley (2005) – with minor processing by Our World in Data. “Life expectancy at birth – Various sources – period tables” [dataset]. Human Mortality Database, “Human Mortality Database”; United Nations, “World Population Prospects”; Zijdeman et al., “Life Expectancy at birth 2”; James C. Riley, “Estimates of Regional and Global Life Expectancy, 1800-2001” [original data]. Retrieved March 5, 2025 from https://ourworldindata.org/grapher/life-expectancy  
</details>

## Source Code
Starter code for this project can be found in the RESOURCES folder. It contains 6 scripts that were previously used to run an analysis. The scripts will give insights on how to combine the datasets and run TWFE and ARIMAX. The scripts are ordered as follows:

1. GDP_csv_organizing.ipynb
2. data_consolidation.ipynb
3. edu_attainment_linear_reg_analysis.ipynb
4. ARIMA_data_cleaning.ipynb
5. TWFE.ipynb
6. full_ARIMAX.ipynb

## Resource References (pdfs in REFERENCES folder)
“14 - Panel Data and Fixed Effects — Causal Inference for the Brave and True.” Accessed: May 06, 2025. [Online]. Available: https://matheusfacure.github.io/python-causality-handbook/14-Panel-Data-and-Fixed-Effects.html

“What Is an ARIMAX Model? | GeeksforGeeks.” Accessed: May 06, 2025. [Online]. Available: https://www.geeksforgeeks.org/what-is-an-arimax-model/

K. Imai and I. S. Kim, “On the Use of Two-Way Fixed Effects Regression Models for Causal Inference with Panel Data,” Polit. Anal., vol. 29, no. 3, pp. 405–415, Jul. 2021, doi: 10.1017/pan.2020.33.

M. Roser, “The global decline of the fertility rate,” Our World in Data, Feb. 2014, Accessed: May 06, 2025. [Online]. Available: https://ourworldindata.org/global-decline-fertility-rate
