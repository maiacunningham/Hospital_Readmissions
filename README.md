# Hospital Readmissions
## Hospital Readmission Modeling using Diabetes Data

Hospital readmissions have been a critical focus of healthcare quality improvement efforts, as they indicate potential gaps in patient care, especially for individuals with chronic conditions like diabetes. Predicting hospital readmissions can help healthcare providers reduce unnecessary readmissions, optimize resource allocation, and improve patient outcomes.

This project utilizes a publicly available dataset on Kaggle, which includes 10 years of hospital readmission data, delineated by various measures of diabetes diagnosis. By analyzing this dataset, the goal is to build a model that can predict the likelihood of hospital readmission based on patient characteristics and medical history.

https://www.kaggle.com/code/p1ayer0ne/hospital-readmissions-eda-and-model

## Methods:
To predict hospital readmissions, I performed data cleaning, feature engineering, and machine learning. The steps included:

**Data Preprocessing:**
Missing values were handled, categorical variables were one-hot encoded, and age categories were converted into numeric values by assigning the average of the age range.

**Model Building:**
A logistic regression model was selected for its interpretability and its suitability for binary classification tasks. We standardized numerical features and encoded categorical variables before fitting the model.

**Evaluation:**
The model's performance was evaluated using key metrics such as accuracy, precision, recall, F1 score, and a confusion matrix. This helped assess the effectiveness of the model in predicting readmissions.

The tools used included:

**Programming Languages:**
R for data processing, model building, and evaluation.

**Packages:**
dplyr for data manipulation, ggplot2 for data visualization, and caTools for data splitting.

## Results:
The model achieved an accuracy of 60.29%, with a 95% confidence interval of (59.18%, 61.4%). The sensitivity (recall) was 77.81%, meaning it correctly identified 77.81% of patients who were actually readmitted. However, the specificity (correctly identifying patients not readmitted) was relatively low at 40.56%. The Kappa statistic was 0.1873, indicating a fair agreement beyond chance, but there is room for improvement. The model's positive predictive value (precision) was 59.60%, suggesting that most of the patients predicted as readmitted were indeed readmitted.

## Potential Impact
The predictive model developed in this analysis has the potential to:
- Improve patient outcomes by allowing healthcare providers to identify high-risk patients and intervene earlier.
- Optimize resource allocation by focusing hospital resources on patients most likely to be readmitted, potentially reducing unnecessary hospitalizations.
- Support healthcare decision-making by integrating predictive analytics into clinical workflows, enhancing decision support tools.
- This project demonstrates the practical application of machine learning in healthcare, showcasing how data-driven approaches can help bridge gaps in patient care and improve efficiency in the healthcare system.
