# Predicting-Short-term-Mortality-in-Heart-Failure-patients

Data Source: Zhang Z, Cao L, Zhao Y, et al. Hospitalized patients with heart failure: integrating electronic healthcare records and external outcome data (version 1.2).  PhysioNet. https://doi.org/10.13026/8a9e-w734


Author: Rodriguez Maria;  2021, January.



Abstract

Background

Despite advances in knowledge and technology, heart failure continues to pose a challenge to health care systems due to its complex nature.  The field is ripe for application of Machine Learning (ML) techniques to work through this complexity and identify possible correlations that have not been detected by conventional research methods. 

Methodology

A dataset comprising of 169 attributes from 2008 patients with heart failure admitted in a single institution from 2016 to 2019 was used.  Data preparation, variable analyses and forecasting was done on a Jupyter platform using python language, pandas, scikit learn (Linear Regression, Random Forest Classifier/ Feature Importances) and statsmodels (Ordinary Least Squares).  

Results

Most of the cohort were aged 69-89 years (67%), 42% were male, majority had chronic congestive heart failure, with both left- and right-heart failures, in NYHA III - IV.  Comorbidities included diabetes (23%) and chronic kidney disease (24%).  The mean left ventricular end-diastolic diameter (LVEDD) was normal at 53 +/- 9 (22-88 mm).  Despite a low mean glomerular filtration rate of 68 ml/min/1.73m2, the median creatinine level was normal.  The mean urea was mildly elevated 10 mmol/L.  The mean brain natriuretic peptide level distribution was elevated (median 744 pg/mL).  Majority (89%) stayed in the hospital for 1-2 weeks.  The mortality rates were:  0.55% in-hospital, 1.25% on the first 7-days after admission, 1.84% at 28-days, and 2.84% at 6 months.  The readmission rate was 40% by the 6th month, with a median time of 83 days from initial admission.  Increased mortality was associated with male gender, low systolic blood pressure (BP), high NYHA classification, high Killip score, low Glascow coma score (GCS), elevated creatine kinase (CK), alanine transaminase (ALT), lactate dehydrogenase (LDH) and creatinine levels, and high O2 requirement.  LVEDD did not show a trend with mortality.  Modelling for 28-day mortality using GCS, Killip score, acute renal failure, ALT and FiO2 requirement showed a p <0..5, R squared 0.23 and predictive accuracy of 99%.

Conclusion

Of the numerous variables available to predict a patient’s outcome, the most important ones can be selected using ML techniques.  The approach yielded a working model with good predictive parameters.
