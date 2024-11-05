# LA Crime Analytics

## Project Overview
This project, **LA Crime Analytics**, aims to analyze and predict criminal activities in Los Angeles using data analytics and machine learning techniques. The study leverages the crime dataset obtained from Kaggle to explore crime indicators, relationships between victim demographics and crime types, and the effectiveness of predictive policing.

The analysis is intended to help law enforcement agencies enhance their understanding of crime patterns and make data-driven decisions regarding crime prevention and resource allocation.

## Course Information
- **Course**: ISDS 577 - Seminar in Information Systems Implementation, Spring 2024
- **Group Members**: 
  - Jeevan Gowda Hemanth Kumar
  - Sai Krishna Mallineni
  - Anwesh Reddy Malgireddy
  - Bala Avinash Allam

## Research Questions
1. **Are there any crime indicators that are proportionate to those with/at risk for crime?**
2. **Is there a correlation between victim age and victim sex? Is there an association between crime factors such as crime description, location, and purpose related to age and sex?**
3. **What is the role of crime attributes like description, location, and date of occurrence in crime prevalence?**
4. **Can machine learning models accurately predict crime based on survey data from this dataset?**
5. **How can data analytics help identify and control crime in relation to area name, victim age, victim sex, and weapons?**

## Data Collection
- **Dataset**: Los Angeles Crimes Dataset obtained from [Kaggle](https://www.kaggle.com/datasets/shayalvaghasiya/los-angeles-crimes).
- **Format**: CSV (Comma Separated Values)
- **Legal Privacy**: The dataset is public and shared under the Community Data License Agreement.
- **Data Attributes**: 247,989 records from 2020 to 2023 with 12 feature variables, including crime area, victim information, crime description, and weapon details.

## Data Preparation
The dataset was cleaned to remove irrelevant variables and missing values. Only data from 2022 to 2023 was retained for analysis. The dataset was split into training and testing sets for machine learning tasks. The data was further cleaned to alleviate any classification imbalance issues.

## Technologies Used
- **Data Analysis and Visualization**: Python, Google Colab, ggplot, pandas
- **Machine Learning**: Scikit-learn (classification models such as logistic regression)
- **Programming Languages**: Python

## Key Insights
- **Crime Indicators**: Data analysis identified key indicators of crime, including crime location, victim age, and victim sex.
- **Crime Patterns**: Analysis showed that areas like the 77th Street Division have the highest crime rates, while other locations such as Van Nuys have lower crime rates.
- **Victim Demographics**: Males have a higher likelihood of becoming victims compared to females, and adults aged 26-44 are the most at-risk age group.

## Machine Learning Models
- Machine learning algorithms were used to predict crime occurrences. The logistic regression model showed promising results, helping predict future crimes based on the dataset.
- **Accuracy**: KNN Random Classifier achieved 80% accuracy in crime prediction.

## Recommendations
1. **Integration with Operations**: Integrate the prediction model into law enforcement operations to improve crime detection.
2. **Resource Allocation**: Allocate police resources effectively to high-risk areas to prevent crime.
3. **Strategic Planning**: Use predictive insights to make informed decisions and take proactive measures to reduce crime rates.

## Usage Instructions
1. **Setup**: Load the crime dataset into Google Drive and mount it in Google Colab.
2. **Data Cleaning**: Run the Python scripts provided in the notebook to clean and preprocess the data.
3. **Data Analysis and Visualization**: Use the provided code to visualize crime patterns and generate insights.
4. **Machine Learning**: Train and test machine learning models to predict crime.

## Future Work
- Improve the accuracy of machine learning models by including more relevant attributes.
- Explore additional datasets for better crime analysis and enhanced predictive capabilities.

## License
This project uses data from Kaggle under the Community Data License Agreement.

## References
- Crime Health Indicator Data: [Kaggle Dataset](https://www.kaggle.com/datasets/shayalvaghasiya/los-angeles-crimes)
- Software and Libraries: Python, Google Colab, ggplot, pandas, scikit-learn
- Contextual Resources: See references in the final report for related literature and studies.
