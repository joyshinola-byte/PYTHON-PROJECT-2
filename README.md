INTRODUCTION

The Titanic dataset is one of the most popular datasets used in data science and machine learning for classification problems. It is based on the historical tragedy of the RMS Titanic ship, which sank on April 15, 1912. The dataset contains information about passengers such as age, gender, ticket class, fare, and survival status.

The main objective of analyzing this dataset is to understand the factors that influenced passenger survival. This project focuses on exploring the dataset, applying statistical analysis, and identifying patterns that affected survival outcomes.


DATASET OVERVIEW

The Titanic dataset contains detailed information about passengers who were on board the ship.

Key Attributes in the Dataset:

PassengerId – Unique ID for each passenger

Survived – Survival status (0 = No, 1 = Yes)

Pclass – Passenger class (1 = First, 2 = Second, 3 = Third)

Name – Passenger name

Sex – Gender of passenger

Age – Age in years

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Ticket – Ticket number

Fare – Ticket fare

Cabin – Cabin number

Embarked – Port of embarkation (C, Q, S

Dataset Characteristics:

Total records: Approximately 891 passengers (in training dataset)

Mixed data types: Numerical and categorical

Some missing values (Age, Cabin, Embarked)

The dataset is suitable for classification tasks and exploratory data analysis.

METHODOLOGY

The dataset was imported using Pandas and cleaned by handling missing values. Data analysis techniques such as filtering, sorting, grouping, and aggregation were applied.

STATISTICAL ANALYSIS

Statistical functions like mean, sum, and groupby() were used to analyze survival rates based on gender, class, age, and fare. Patterns affecting survival were identified through descriptive analysis.

CONCLUSION

The analysis of the Titanic dataset reveals that survival was strongly influenced by gender, passenger class, and age.

Key findings:

Women and children were more likely to survive.

First-class passengers had higher survival probability.

Higher ticket fare was associated with better survival chances.

Third-class male passengers had the lowest survival rate.

This project demonstrates how statistical analysis and data preprocessing can help uncover meaningful patterns from historical data. The Titanic dataset serves as a foundational example for learning classification and predictive modeling techniques in data science.
