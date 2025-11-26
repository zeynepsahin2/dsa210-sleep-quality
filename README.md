# dsa210-sleep-quality

Project Overview:
This project will focus on daily nutrition intake effects sleep quality. By collecting personal data over several weeks, I will analyze what correlation meal timing, macronutrients (carbohydrates,protein,fat),water intake, the weather and physical activity have with sleep duration and quality.

Motivation:
As someone who cares about my sleep quality, I always look for ways on how to enhance my sleeping experience. There has been lots of different opinions on how to get better sleep and a lot of these opinions form around lots of lifestyle choices.
Also with the recent developments in nutrition science, people started to pay attention to their nutrition intake more. Weather is also another known factor for energy levels. Physical activity is another aspect that affects energy and well-being levels. This project will be a guide for individuals to determine what factors affect their overall well-being. 

Data Used:
- Date
- Last meal Time
- Daily Carbohydrate Amount
- Daily Protein Amount
- Daily Fat Amount
- Daily Water Intake
- The Weather (temperature, condition)
- Physical Activity
- Daily Sleep Duration
- Daily Sleep Quality
  
Data Collection: 
The way data will be collected for this project is daily manual entries for 20 days in CSV format
  - Daily macronutrition values will be obtained by using a calorie tracker app on my phone
  - Daily water intake will be obtained by using a tracker app on my phone
  - Daily sleep duration will be obtained by using my Apple Watch's sleep tracking function
  - Daily sleep quality will be obtained by personal input, (on a scale of 0-10)
  - The weather will be obtained via a public source (temperature, condition)
  - Daily physical activity will be a manual entry (yes,no)
  - Daily physical activity duration will be obtained by my Apple Watch Fitness app

Exploratory Data Analysis (EDA) Plan:

  - I will examine the distributions of all daily variables using histograms and boxplots.
  - I will compute Pearson and Spearman correlations between macronutrients, water intake, weather variables,        physical activity and sleep quality.
  -I will compare mean sleep quality across categorical groups such as caffeine vs no caffeine, exercise vs no       exercise and early vs late last meal times.
  -I will produce a correlation heatmap to identify key relationships between features.

  Hypothesis Tests

  -I will formally test the following hypotheses:
  	1.	H1: Sleep quality is lower on days with caffeine intake.
        Test: Two-sample t-test or Mann–Whitney test (will be chosen based on the data)
  	2.	H2: Eating later in the evening reduces sleep duration.
        Test: Two-sample t-test
  	3.	H3: Higher sugar or carbohydrate intake is associated with lower sleep quality.
        Test: Pearson/Spearman correlation and significance of regression slope
  	4.	H4: Sleep quality is higher on days with physical activity.
        Test: Two-sample t-test



  Prediction Model

  Target variable: Daily Sleep Quality (0–10)

    Predictors:
    Last meal time
    Carbohydrate, protein, fat intake
    Water intake
    Weather variables (temperature, condition)
    Physical activity indicators
    Sleep duration
    
    Models to be used:
    Linear Regression to interpret coefficients
    Decision Tree Regression to analyze feature importance
    
    Evaluation metrics:
    MAE
    RMSE
    R²

  The prediction phase will identify which factors have the strongest influence on sleep quality based on the       collected features.
