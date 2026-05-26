Bellabeat Fitness Tracker Data Analysis
Project Overview

Bellabeat is a wellness technology company that develops smart devices focused on health tracking and lifestyle improvement. 
The objective of this project is to analyze smart fitness device usage data and identify trends in user activity, sleep behavior, and device engagement. 
The insights generated from this analysis can help Bellabeat improve its marketing strategy and user experience.

Business Task

Analyze non-Bellabeat fitness tracker data to identify behavioral patterns and trends that can support Bellabeat's marketing decisions 
and encourage healthier lifestyles among users.

Dataset

The dataset used in this project is the Fitbit Fitness Tracker Data available on Kaggle.

Data source:

Fitbit Fitness Tracker Data (Mobius, Kaggle)

Files used:

dailyActivity_merged.csv
sleepDay_merged.csv
Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Tableau Public
Microsoft Excel
Data Preparation

The following data cleaning and preprocessing steps were performed:

Imported datasets using Pandas
Checked dataset structure and data types
Verified dataset dimensions
Identified and removed duplicate records
Checked for missing values
Converted date columns to datetime format
Merged activity and sleep datasets using:
User ID
Date
Feature Engineering

A new feature was created:

AwakeInBed_minutes

Calculated as:

AwakeInBed_minutes = TotalTimeInBed − TotalMinutesAsleep

This metric measures the amount of time users spend awake while in bed.

Exploratory Data Analysis
Activity Analysis

Analyzed:

Total Steps
Calories Burned
Active Minutes
Sedentary Minutes

Generated summary statistics:

Minimum
Median
Maximum
Total
Sleep Analysis

Analyzed:

Total Minutes Asleep
Total Time in Bed
Total Sleep Records
Awake In Bed Minutes
User-Level Analysis

Grouped data by user ID and calculated aggregated statistics to identify individual behavior patterns.

Visualizations

The following visualizations were created:

Daily Steps vs Calories Burned (Scatter Plot)
Distribution of Daily Steps (Histogram)
Average Sleep Duration by User (Bar Chart)
Average Time Awake in Bed by User (Bar Chart)
Correlation Heatmap
Activity vs Sleep Relationship Analysis

Visualizations were developed using Python and Tableau Public.

Key Insights
Insight 1

A positive relationship exists between daily steps and calories burned. 
Users who walk more steps generally burn more calories.

Insight 2

Many users do not consistently achieve the commonly recommended daily activity target of 10,000 steps.

Insight 3

Average sleep duration among several users is below the recommended eight hours per night.

Insight 4

There is considerable variation in activity levels between users, 
suggesting different fitness habits and engagement levels.

Insight 5

Some users spend a significant amount of time awake while in bed,
indicating potential opportunities for sleep quality improvement.

Recommendations
1. Personalized Activity Reminders

Implement personalized notifications encouraging users to reach daily step goals based on their activity history.

2. Sleep Improvement Features

Provide bedtime reminders, sleep quality insights, and relaxation recommendations to help users improve sleep habits.

3. Behavioral Segmentation

Segment users according to activity and sleep patterns and deliver tailored wellness recommendations.

4. Gamification Strategy

Introduce achievement badges, challenges, and rewards to increase user engagement and encourage consistent device usage.

5. Data-Driven Wellness Coaching

Use collected health metrics to generate personalized wellness suggestions and actionable health goals.

Limitations
Small sample size (33 users)
Limited sleep data availability (24 users)
No demographic information
Dataset collected during a limited time period
Data originates from Fitbit users and may not fully represent Bellabeat's target audience
Conclusion

The analysis revealed meaningful patterns in physical activity, sleep behavior, and user engagement. These findings can help Bellabeat design targeted marketing campaigns, improve user retention, and develop personalized wellness experiences that encourage healthier lifestyles.
