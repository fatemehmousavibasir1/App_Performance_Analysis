# Notification Data Analysis 

This project presents a comprehensive data analysis of notification delivery and performance metrics using data from **Pushe** — a push notification service used by many mobile and web applications. The analysis focuses on understanding user engagement patterns, notification efficiency, and overall app performance based on notification response behavior.

## About Pushe

**Pushe** is an Iranian push notification service designed for mobile and web platforms. Businesses and developers integrate Pushe's SDK into their applications to:

- Increase user retention and engagement.
- Deliver targeted and timely notifications.
- Gain actionable insights through advanced analytics.
- Optimize notification strategies using segmentation and filtering tools.

This project analyzes real notification data provided by Pushe in order to uncover patterns of user engagement and provide recommendations for more effective notification delivery.

## Project Structure

This project consists of several analytical steps, implemented using Jupyter Notebooks. Each notebook explores a different aspect of the notification data:

```
.
├── App_Performance_Analysis.ipynb
├── notifications_pushe.csv
└── README.md
```

## Objectives

This project aims to answer key business and technical questions related to notification performance:

- Which application has the most effective notification strategy (highest CTR)?
- Which notification was the most engaging?
- When is the best time to send notifications to maximize clicks?
- How do users respond to notifications over different days of the month?

## Analysis Breakdown

### 1. App Performance Analysis

- **Goal**: Evaluate the effectiveness of push notifications across different applications.
- **Method**:
  - Compute Click-Through Rate (CTR) for each app:
    CTR = (Number of Clicks / Number of Delivered Notifications) × 100
  - Identify the application with the highest CTR, signifying the most engaging notification strategy.

### 2. Notification Performance Analysis

- **Goal**: Determine the most successful notification and the optimal day of the week for engagement.
- **Method**:
  - Calculate CTR for each notification.
  - Identify the notification with the highest CTR.
  - Analyze the day of the week it performed best.
- **Key Questions**:
  - Which notification generated the most clicks?
  - Does performance vary by weekday?

### 3. Click Rate Analysis by Day of the Month

- **Goal**: Understand temporal patterns in user engagement.
- **Method**:
  - Aggregate click data across each day of the month.
  - Visualize engagement trends to identify peaks and low-activity days.
- **Insights**:
  - Are users more likely to click on certain dates?
  - Do monthly cycles (e.g., salary days, weekends) affect user behavior?

## Sample Metrics

During the analysis, the following key performance indicators are used:

- CTR (Click-Through Rate)
- Notification Engagement Ratio
- App-level Notification Delivery
- Day-wise Click Distribution
- Most Engaging Notification ID

## Technologies & Tools

The project is developed using the following stack:

- Python: Core language for analysis.
- Pandas: Data manipulation and cleaning.
- NumPy: Numerical computation.
- Matplotlib / Seaborn / Plotly: Data visualization.
- Jupyter Notebook: Interactive data exploration.
