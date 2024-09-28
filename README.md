# Diabetes Analysis Using Statistical Programming

## Introduction
Diabetes, a major global health concern, affects millions of people worldwide. In the U.S., as of 2021, 38.4 million individuals, or about 11.6% of the population, have diabetes. This project focuses on analyzing factors contributing to diabetes prevalence in the U.S., specifically Type 2 Diabetes, using data from the Behavioral Risk Factor Surveillance System (BRFSS). Statistical and machine learning techniques are employed to identify significant predictors of diabetes and assess their impact.

## Dataset
The dataset used for this analysis is publicly available on Kaggle: [Kaggle Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

## Objectives
1. **Health-Related Factors**: Evaluate the association between health-related factors (BMI, high blood pressure, cholesterol levels, and physical activity) and the likelihood of diabetes.
2. **Lifestyle Behaviors**: Determine the predictive power of lifestyle behaviors (smoking, alcohol consumption, and mental health) on diabetes risk.
3. **Socioeconomic Factors**: Analyze the influence of socioeconomic factors (age, education, income) on diabetes prevalence and assess their potential as predictors in diabetes risk models.

## Methodology
This project utilizes a variety of statistical techniques, including:
1. **Data Preprocessing**: Handling missing values, converting variables to appropriate data types (e.g., categorical or integer), and summarizing descriptive statistics.
2. **Inferential Statistics**:
    - Chi-Square Tests to assess the independence of categorical variables.
    - T-tests for comparing means of health-related factors like BMI between diabetes and non-diabetes groups.
3. **Statistical Modelling**: Logistic Regression is employed to model the likelihood of diabetes based on health, lifestyle, and socioeconomic factors.
4. **Model Diagostics**: Evaluating model fit using metrics like the Akaike Information Criterion (AIC) and McFadden’s R-squared, and interpreting odds ratios to understand the strength of associations.
5. **Prediction and Validation**: The Receiver Operating Characteristic (ROC) curve and Area Under the Curve (AUC) are used to assess the model's performance.

## Key Findings
### Objective 1: Health-Related Factors
- **High Blood Pressure**: Individuals with high blood pressure are 3.4 times more likely to have diabetes.
- **Cholesterol Levels**: Those with high cholesterol levels have a 2.2 times higher chance of developing diabetes.
- **Physical Activity**: Engaging in physical activity reduces the risk of diabetes by 33%.

### Objective 2: Lifestyle Behaviors
- **Smoking**: Smokers have 1.43 times higher odds of developing diabetes compared to non-smokers.
- **Alcohol Consumption**: Heavy alcohol consumption is associated with lower odds of diabetes.
- **Mental Health**: Increased mental health issues slightly elevate the risk of diabetes.

### Objective 3: Socioeconomic Factors
- **Income and Education**: Lower income and educational levels are linked with higher odds of developing diabetes.
- **Age**: Older age groups have a significantly higher risk of diabetes.

## Conclusion
This project provides a comprehensive analysis of factors contributing to diabetes prevalence in the U.S. By utilizing inferential statistics and logistic regression models, we identify key health, lifestyle, and socioeconomic predictors that significantly impact the risk of developing diabetes. These findings can inform public health interventions aimed at reducing diabetes risk.
