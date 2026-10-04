## **📊 Social Media Engagement Analysis | 5,000 Posts**

Python-based analysis of 5,000 social media posts to uncover engagement trends across post types, content categories, countries, devices, sentiment, and user demographics.

Focus: Data Cleaning, EDA, Statistical Analysis, Visualization, and Business Insights.

## **🎯 Project Objectives**

- The main objectives of this project are to:
  
Analyze social media engagement patterns and drivers
Identify best-performing post types, content categories, and countries
Examine relationship between user demographics (age, verification) and engagement
Analyze impact of device type, sentiment, and posting time on performance
Investigate relationships between impressions, likes, watch time, followers, and engagement rate
Handle outliers and improve distribution using log transformation

## **✨ Key Features Engineered**

- hashtag_count - Number of hashtags per post
- engagement_score - Weighted score = (Likes × 1) + (Comments × 2) + (Shares × 3)
- engagement_rate_log - Log-transformed engagement rate for normality

  
## **🛠️ Tech Stack**

Python - Pandas, NumPy, SciPy

Visualization - Matplotlib, Seaborn

Environment - Google Colab / Jupyter Notebook


## **🔄 Workflow**

1. Data Import & Cleaning - Type conversion, missing value treatment, duplicate removal
2. Standardization & Validation - Country, device, sentiment standardization
3. Feature Engineering - Hashtag count, engagement score, log transformation
4. EDA & Outlier Analysis - Distribution analysis, boxplots, IQR method
5. Correlation & Statistical Analysis
6. Visualization & Business Insights

## **📈 Exploratory Data Analysis**

Content Performance: Post Type, Category, Country analysis
User Trends: Age group, Gender, Verified vs Non-Verified
Behavioral Insights: Device type, Posting time (date-based)
Sentiment Analysis: Positive, Negative, Neutral performance

## **📊 Visualizations**

Matplotlib: Daily engagement trend, Category distribution, Gender distribution, Likes vs Impressions scatter
Seaborn: Follower distribution by sentiment, Correlation heatmap, Post type distribution, Pairplot, Engagement rate & Log distribution

## **🔎 Key Correlations (Observational)**

impression_count vs engagement_rate: -0.23 (negative association - higher reach, lower rate)
likes vs engagement_rate: 0.09 (weak positive)
age vs engagement_rate: 0.01 (very weak - almost no association)

## **💡 Final Business Insights**

Content: Image posts lead with highest engagement. Top category is Fitness/Travel. Top country shows regional preference.
User: 18-24 age group is most engaged. Weak negative age-engagement correlation. Verified accounts outperform non-verified in engagement, impressions, and watch time.
Behavioral: Time-of-day analysis not supported - posted_at has dates only. Mobile dominates watch time.
Sentiment: Positive sentiment performs best. Negative drives debate but lower watch time than Neutral.

## **📁 Dataset**

social_media_engagement_5000.csv - 5,000 rows with columns: post_type, post_category, country, age, is_verified, device_type, sentiment, engagement_rate, impression_count, watch_time_sec, likes, etc.

## **🚀 How to Run**

import pandas as pd
url = "https://raw.githubusercontent.com/GeethaGunasekaran1/Dataset_rep/main/social_media_engagement_5000.csv"
df = pd.read_csv(url)

**Author** 

Priyadharshini Naresh D 

AI Driven Data Analysts 
