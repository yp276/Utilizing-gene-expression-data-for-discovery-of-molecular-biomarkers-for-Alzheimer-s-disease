# Utilizing-gene-expression-data-for-discovery-of-molecular-biomarkers-for-Alzheimer-s-disease
Exploratory Analysis of Genomic Biomarkers for  Severe Alzheimer’s Disease in R 

This repository contains files/code for Georgetown HIDS 7003 (Precision Health Informatics) Midterm Project. This project explores the relationship between age and REM sleep in healthy adults using statistical analysis in R.

Introduction:
In this study we have attempted to look into the correlation between age and one of the most unique phase of sleep - rapid-eye movement. The rapid-eye movement phase (REM) is distinguished by muscle relaxation, rapid eye movements, irregular breathing, increased heart rate, and heightened brain activity. REM sleep serves various functions, including memory consolidation, emotional processing, brain maturation, and dream generation. Research conducted by Floyd et al. in a meta-analysis revealed a gradual decline in the proportion of REM sleep by 0.6% per decade from age 19 until the age of 75. Afterward, slight increases were observed in the proportion of REM sleep between the ages of 75 and 85 (Floyd et al.).

Dataset:
The dataset used for this project can be found at: Kaggle Sleep Efficiency Dataset.

Hypothesis:
We define healthy adults in accordance with CDC, FDA, and Mayo Clinic guidelines. Specifically, the CDC defines healthy adults as non-smokers and who exercise 150 minutes of moderate-intensity physical activity/week (Center for Disease Control and Prevention, 2022). The FDA defines 400 mg caffeine/day, which is about 4-5 cups of coffee, for healthy adults (Commissioner, 2023). The Mayo Clinic defines moderate alcohol use for healthy adults as 2 drinks/day for men and 1 drink/day for women (Mayo Foundation for Medical Education and Research, 2021). For reference, a beer is 12 oz, wine is 5 oz, and distilled spirits are 1.5 oz.

Thus, this leads naturally to the setting of the hypothesis. Null hypothesis: there is no association between REM sleep and age in healthy adults.

Steps:
-Installed packages and read in the .CSV file -Differentiated the key variables and confounders -Performed Exploratory Data Analysis (EDA) -Checked for any issues with data quality -Check assumptions of normality of REM -Graphed visual representations: histograms -Conducted hypothesis testing: Welch's T-test, Simple linear regression, Multiple linear regression -Interpreted results via statistical analysis
