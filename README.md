📊 Project:
Analysing the effectiveness of Lockdown and Covid-19 Vaccinations together in it's effectiveness in increasing mobility after Covid-19

📘 Overview
This project explores how government lockdowns and vaccination efforts affected urban mobility in Thailand during the Covid-19 peak period (April–December 2021). Thailand, the first country outside China to report a Covid-19 case, experienced its worst outbreak in August 2021. We compare mobility patterns across two lockdown phases (2020 vs 2021), assess the impact of daily cases and vaccination rates on mobility, and evaluate sector-wise changes in movement behavior.

🎯 Research Questions
How did mobility patterns differ between Thailand's first (2020) and peak (2021) lockdowns?
What was the impact of daily Covid-19 cases on overall and sector-specific mobility?
Did the vaccination programme reduce mortality and help restore mobility?
How did vaccinations influence different types of urban mobility?

🗃️ Data Sources
Google Global Mobility Reports: Daily % change in six mobility sectors.
Our World in Data (OWID): Covid-19 cases, deaths, vaccinations, and policy responses.

⚙️ Methods
Feature Engineering: Created overall mobility index as the mean of 5 categories (excluding residential).
Data Processing: Filtered for Thailand; used z-score standardization for time series trend comparison.
Exploratory Analysis: Used Pearson correlation and scatter plots.

Statistical Tests:
2-Way ANOVA: To compare mobility across two lockdowns.
Toda-Yamamoto Causality Test: To assess cause-effect relationships between:
Covid cases ↔ Mobility
Vaccination ↔ Mortality
Vaccination ↔ Mobility (overall and by sector)

📌 Key Tools
Python (Pandas, NumPy, Statsmodels)
Google Mobility & OWID datasets
Statistical modeling (ADF, KPSS, ANOVA, TY Causality)
