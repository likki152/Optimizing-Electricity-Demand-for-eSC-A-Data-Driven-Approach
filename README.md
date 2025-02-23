# Optimizing-Electricity-Demand-for-eSC-A-Data-Driven-Approach

## Project Overview
This project focuses on optimizing electricity demand for eSC, an energy company serving residential properties in South Carolina and parts of North Carolina. The goal is to reduce energy consumption during peak summer months, particularly in July, through data-driven strategies rather than expanding energy production facilities.

## Team Members
- Likhith Kolli
- Vishnu Charugundla
- Lekhith Reddy Kambham
- Prathyusha Murala
- Austin Rodrigues

## Problem Statement
eSC faces challenges in managing increased energy demand, especially during extreme summer temperatures. The company aims to prevent blackouts and ensure sustainability by understanding key factors influencing electricity consumption and encouraging energy-saving practices.

## Objectives
1. **Optimize Energy Usage:** Develop strategies to manage peak electricity demand.
2. **Identify Key Drivers:** Analyze house attributes, energy usage patterns, and weather conditions.
3. **Encourage Energy-Saving Practices:** Recommend changes for reducing electricity consumption.
4. **Predict Future Energy Demand:** Build and evaluate machine learning models for forecasting.
5. **Simulate "Extra Hot" Scenarios:** Model energy demand with July temperatures increased by 5°C.
6. **Develop a Shiny Application:** Provide an interactive platform for stakeholders to visualize results.

## Data Sources
- **Static House Data:** Contains attributes of 5,000+ single-family homes.
- **Energy Usage Data:** Hourly energy consumption logs for each house.
- **Weather Data:** Hourly weather conditions across 50 counties.
- **Meta Data:** Provides descriptions of all dataset fields.

## Methodology
1. **Data Preparation:**
   - Merging house, energy, and weather data.
   - Cleaning missing values and standardizing formats.
   - Feature engineering for model optimization.
  
2. **Exploratory Data Analysis (EDA):**
   - Identified key consumption trends based on county, cooling systems, occupancy, and weather.
   - Analyzed the impact of temperature setpoints on energy demand.

3. **Modeling:**
   - Applied Linear Regression, Random Forest, and XGBoost models.
   - Evaluated performance using MAE and R-squared metrics.
   - Selected the best-performing model for forecasting.
   - Simulated energy demand changes with increased temperatures.

4. **Interactive Dashboard (Shiny App):**
   - Developed an interactive web application to visualize energy demand insights.
   - URL: [Shiny Dashboard](https://klikhith.shinyapps.io/final_shiny/)

## Key Findings
- **Cooling systems account for 60%+ of household electricity usage.**
- **Increasing thermostat setpoints from 72°F to 75°F reduces consumption by 20%.**
- **July 3rd is predicted to have the highest energy demand.**
- **Charleston and Sumter counties have the highest electricity consumption.**
- **Simulated 5°C temperature increases resulted in a 31.53% rise in electricity usage.**

## Recommendations
1. **Demand-Side Management:**
   - Implement time-of-use pricing to incentivize off-peak usage.
   - Offer financial rewards for reducing electricity consumption during peak hours.

2. **Technology-Driven Solutions:**
   - Deploy smart meters and Home Energy Management Systems (HEMS).
   - Utilize machine learning models for demand forecasting.
   - Introduce demand response programs to manage peak loads.

3. **Policy & Community Engagement:**
   - Advocate for energy efficiency standards and renewable incentives.
   - Educate consumers on sustainable energy habits.
   - Develop community-based solar energy projects.

## Project Deliverables
- **Final Report:** Detailed analysis of findings and recommendations.
- **Presentation:** Summary of project insights.
- **Shiny App:** Interactive visualization tool for stakeholders.

## Team Contributions
- **Data Preparation & Cleaning:** Vishnu, Likhith K.
- **Exploratory Data Analysis:** Prathyusha, Lekhith R.
- **Model Development & Evaluation:** Vishnu, Likhith K., Austin
- **Visualization & Dashboard Development:** Austin, Likhith K.
- **Report & Presentation Preparation:** Entire team

## Technologies Used
- **Programming Languages:** R, Python
- **Libraries & Tools:** dplyr, ggplot2, caret, XGBoost, Shiny
- **Data Storage:** Parquet & CSV files

## Future Work
- Extend forecasting models to other seasons.
- Enhance Shiny app with real-time weather and energy data.
- Explore deeper customer segmentation for targeted recommendations.

---

For more details, refer to the [Final Report](./Group-5-Project-Report.pdf) and [Presentation](./Optimizing-Electricity-Demand-for-eSC-A-Data-Driven-Approach.pptx).
