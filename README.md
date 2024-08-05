# Vaccine Prediction Project
Predicting Flu Vaccine Uptake Using Machine Learning
<h1>Project Description:</h1>
This project aims to develop a predictive model to estimate the likelihood of individuals receiving two types of flu vaccines: the XYZ flu vaccine and the seasonal flu vaccine. The analysis utilizes a dataset with various features related to demographic information, health behaviors, medical recommendations, and personal opinions on vaccine effectiveness and risks.This project will provide insights into factors influencing flu vaccine uptake and demonstrate the application of machine learning techniques in public health analytics.
<h1>Deliverables:</h1>
<h3>Predictive Model</h3>
A trained machine learning model capable of predicting the probabilities of receiving each vaccine.
<h3>Evaluation Report</h3>
A detailed report on model performance, including ROC AUC scores for both target variables.
<h3>Submission File:</h3>
A CSV file containing the respondent IDs and the predicted probabilities for each vaccine.
## Dataset

The dataset consists of 36 columns, where the first column is a unique respondent identifier, and the remaining 35 columns are features describing the respondent's behavior, opinions, and demographics. The labels for the prediction task are binary variables indicating whether the respondent received the xyz vaccine and the seasonal flu vaccine.

## Features

- `xyz_concern`: Level of concern about the xyz flu.
- `xyz_knowledge`: Level of knowledge about xyz flu.
- `behavioral_antiviral_meds`: Has taken antiviral medications. (binary)
- `behavioral_avoidance`: Has avoided close contact with others with flu-like symptoms. (binary)
- `behavioral_face_mask`: Has bought a face mask. (binary)
- `behavioral_wash_hands`: Has frequently washed hands or used hand sanitizer. (binary)
- `behavioral_large_gatherings`: Has reduced time at large gatherings. (binary)
- `behavioral_outside_home`: Has reduced contact with people outside of own household. (binary)
- `behavioral_touch_face`: Has avoided touching eyes, nose, or mouth. (binary)
- `doctor_recc_xyz`: xyz flu vaccine was recommended by doctor. (binary)
- `doctor_recc_seasonal`: Seasonal flu vaccine was recommended by doctor. (binary)
- `chronic_med_condition`: Has any chronic medical conditions. (binary)
- `child_under_6_months`: Has regular close contact with a child under the age of six months. (binary)
- `health_worker`: Is a healthcare worker. (binary)
- `health_insurance`: Has health insurance. (binary)
- `opinion_xyz_vacc_effective`: Respondent's opinion about xyz vaccine effectiveness.
- `opinion_xyz_risk`: Respondent's opinion about risk of getting sick with xyz flu without vaccine.
- `opinion_xyz_sick_from_vacc`: Respondent's worry of getting sick from taking xyz vaccine.
- `opinion_seas_vacc_effective`: Respondent's opinion about seasonal flu vaccine effectiveness.
- `opinion_seas_risk`: Respondent's opinion about risk of getting sick with seasonal flu without vaccine.
- `opinion_seas_sick_from_vacc`: Respondent's worry of getting sick from taking seasonal flu vaccine.
- `age_group`: Age group of respondent.
- `education`: Self-reported education level.
- `race`: Race of respondent.
- `sex`: Sex of respondent.
- `income_poverty`: Household annual income of respondent with respect to 2008 Census poverty thresholds.
- `marital_status`: Marital status of respondent.
- `rent_or_own`: Housing situation of respondent.
- `employment_status`: Employment status of respondent.
- `hhs_geo_region`: Respondent's residence using a 10-region geographic classification defined by the U.S. Dept. of Health and Human Services.
- `census_msa`: Respondent's residence within metropolitan statistical areas (MSA) as defined by the U.S. Census.
- `household_adults`: Number of other adults in household, top-coded to 3.
- `household_children`: Number of children in household, top-coded to 3.
- `employment_industry`: Type of industry respondent is employed in.
- `employment_occupation`: Type of occupation of respondent.

## Files

- `training_set_features.csv`: Training set features.
- `training_set_labels.csv`: Training set labels.
- `test_set_features.csv`: Test set features.
- `submission_format.csv`: Sample submission file format.

# Evaluation Metrics
The primary metric for evaluating the models is the ROC AUC score. Additional metrics such as precision, recall, and F1-score are also considered.

# Insights and Interpretability
The project provides insights into the significant factors influencing vaccination probabilities using techniques like feature importance and SHAP values.

# Contributing
Contributions are welcome. Please submit a pull request or open an issue to discuss changes.
