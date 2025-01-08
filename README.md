# Analysis of Sleep Quality Data and Related Factors
## Introduction
Sleep health is a critical component of overall well-being, influencing physical, mental, and emotional health. This project delves into the intricate relationship between various factors such as occupation, gender, BMI, stress levels, physical activity, and age, and their impact on sleep patterns and disorders.

Using advanced data analysis techniques and visualization tools, this study provides a comprehensive exploration of the patterns and trends affecting sleep quality and duration. The findings aim to uncover actionable insights that can aid in developing effective strategies for improving sleep health across different demographics.
## Objective
The objective of this project is to analyze the sleep and health data provided by SleepInc, focusing on identifying patterns and relationships between factors such as physical exercise, gender, occupation, stress levels, and sleep quality. The analysis aims to provide insights into the factors directly impacting sleep quality and how these factors can be manipulated to improve the well-being of SleepScope app users.

## The data: sleep_health_data.csv
The dataset provided contains information about 374 individuals and includes 13 variables related to sleep habits, physical health, and demographic characteristics for each person calculated over the past six months. The data is saved as `sleep_health_data.csv`. The variables include:
| Column | Description |
|---------|----------------------------------------|  
| `Person ID` | An identifier for each individual. |
| `Gender` | The gender of the person (Male/Female). |  
| `Age` | The age of the person in years. |
| `Occupation` | The occupation or profession of the person. |
| `Sleep Duration (hours)` | The average number of hours the person sleeps per day. |
| `Quality of Sleep (scale: 1-10)` | A subjective rating of the quality of sleep, ranging from 1 to 10. |
| `Physical Activity Level (minutes/day)` | The average number of minutes the person engages in physical activity daily. |  
| `Stress Level (scale: 1-10)` | A subjective rating of the stress level experienced by the person, ranging from 1 to 10. |
| `BMI Category` | The BMI category of the person (e.g., Underweight, Normal, Overweight). |
| `Blood Pressure (systolic/diastolic)` | The average blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure. |
| `Heart Rate (bpm)` | The average resting heart rate of the person in beats per minute. |
| `Daily Steps` | The average number of steps the person takes per day. |
| `Sleep Disorder` | The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea). |

## Technologies Used to Perform the Project:

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original-wordmark.svg" alt="Python" width="50" />  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original-wordmark.svg" alt="Pandas" width="50" />  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original-wordmark.svg" alt="Numpy" width="50" />  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" width="50" />  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" alt="Scikit-learn" width="50" />  
  <img src="https://raw.githubusercontent.com/scipy/scipy.org/b267bf3961d344c7d45b9452c51287819c97f55e/static/images/logo.svg" alt="SciPy" width="50" />  
  <img src="https://raw.githubusercontent.com/mwaskom/seaborn/master/doc/_static/logo-wide-lightbg.svg" alt="Seaborn" width="100" />
</p>      

## Methodology
1. **Loading and Initial Data Exploration:** The dataset was loaded, and its structure was explored to identify missing values and inconsistencies. Descriptive statistical analysis was conducted to understand variable distributions.
2. **Data Cleaning and Preprocessing:** Missing values were handled, and variables were reformatted for analysis. Outliers were examined and addressed where appropriate.
3. **Exploratory Analysis:** Key relationships were analyzed, including:
     - *Correlation Between Physical Activity and Sleep Quality:* Scatter plots and Pearson correlation coefficients were used to explore the relationship.
     - *Impact of Gender on Sleep Quality:* Box plots visualized differences in sleep quality distributions between genders.
     - *Occupation and Sleep Quality:* Box plots compared sleep quality across different occupations.
     - *Effect of Stress on Sleep Quality:* Scatter plots and correlation coefficients assessed the negative impact of stress levels on sleep quality.
4. **Visualizations:** Various graphs such as histograms, scatter plots, box plots, and pair plots were generated for intuitive insights into the relationships between variables.

## Insights and Conclusions
The sleep health analysis revealed several factors that significantly influence both sleep quality and duration across different groups. Occupation plays a key role, with sales representatives showing the lowest sleep quality and duration. Occupations such as nurses and sales representatives are highly associated with sleep disorders like sleep apnea, while teachers and accountants tend to suffer more from insomnia.

In terms of gender, females have significantly better sleep quality than males, with an average of 7.66 compared to 6.97, and a higher prevalence of sleep apnea (65.05%), while males have a higher proportion of insomnia (78.85%). Statistical analysis also showed significant differences between genders and sleep quality, with a p-value < 0.00000001.

Age group also influences sleep patterns, with individuals in the 50-60 age group having the highest sleep quality (8.16), and the prevalence of sleep apnea reaching 86.21% in this group. Insomnia, on the other hand, is more common in the 40-50 age group (80%).

Regarding body mass index (BMI), it was observed that higher BMI categories, such as overweight and obesity, are strongly associated with sleep apnea, especially among the obese, with a 60% prevalence. However, correlation analysis did not reveal a significant direct relationship between BMI categories and sleep disorders overall (correlation = 0.02).

Additionally, higher stress levels and lack of physical activity are factors that also impact sleep quality, with stress being a strong indicator of poorer sleep quality.

These findings suggest that a comprehensive focus on factors such as gender, age, occupation, BMI, and stress levels is essential for improving sleep health. Strategies to mitigate sleep disorders should consider the interaction of these multiple factors to be more effective.

## Recommendations:

1. Implement features in the app to monitor and encourage physical activity.
2. Provide stress management tools and resources.
3. Personalize sleep improvement plans based on occupation and BMI to address specific sleep challenges.

## Next Steps:

- [ ] Use these findings to enhance the SleepScope app with personalized recommendations.
- [ ] Develop new features targeting stress and physical activity management to improve sleep quality.


