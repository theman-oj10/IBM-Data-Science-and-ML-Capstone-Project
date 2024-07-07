![image](https://github.com/theman-oj10/IBM-Data-Science-and-ML-Capstone-Project/assets/85360326/b378afec-553f-4c62-997c-92b1a0d09dfe)# IBM-Data-Science-and-ML-Capstone-Project
IBM Data Science and ML Capstone Project

#### Project Background and Context:
Objective: Analyze SpaceX launch data to uncover patterns, improve launch success rates, and predict outcomes.
Context: SpaceX's frequent launches require data-driven insights to optimize performance and safety.

**Problems to Find Answers:**
Which launch sites are most successful?
How does payload mass affect launch success?
What are the yearly trends in launch success rates?
Which machine learning model best predicts launch success?

#### Executive Summary

#### Summary of Methodologies:
**Data Collection:**
SpaceX REST API: Collected launch data.
Web Scraping: Gathered additional data from Wikipedia using BeautifulSoup.
**Data Processing:**
Parsed data into Pandas DataFrame.
Cleaned and normalized data.
Created calculations and determined useful labels.
**Model Development:**
Built models: Logistic Regression, SVM, K-Nearest Neighbors.
Evaluated using accuracy, precision, recall, F1-score.
Improved through hyperparameter tuning and feature scaling.
**Visualization:**
Created interactive plots (bar charts, scatter plots, line charts, pie charts, maps) for insights.

#### Summary of All Results:
Launch Success Rates: Highest at KSC-LC-39A, lowest at CCAFS SLC 40.
Payload Impact: Heavier payloads (>8000 kg) generally successful.
Yearly Trends: Increased launch frequency and success over time, except in 2018.
Model Performance: Logistic Regression, SVM, KNN showed highest accuracy (0.8333).



