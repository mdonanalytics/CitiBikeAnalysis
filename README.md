
# CitiBike Data Insights: Analyzing User Behavior and Trip Patterns

# Overview
This project aims to analyze and visualize NYC CitiBike trip data for non-technical end users. This demo highlights the use of Tableau for data visualization and Python for data analysis.

# Purpose
The primary goal of this project is to provide an interactive and dynamic dashboard that allows users to explore the CitiBike dataset to uncover patterns and trends that could help improve bike-sharing services and user experience.

# Insights

The full analysis can be found on Tableau Public here: https://shorturl.at/7RUBk

High level highlights
- Nearly 50% of riders with known gender are male.

- Generation Alpha accounts for 42% of users.
 
<img width="795" alt="Screenshot 2024-11-14 at 4 15 46 PM" src="https://github.com/user-attachments/assets/698c2053-3214-4c7d-bd16-8989244125b8">

- The average ride time is approximately 23 minutes.

<img width="792" alt="Screenshot 2024-11-14 at 4 15 34 PM" src="https://github.com/user-attachments/assets/5279dea6-e408-44ea-8cdb-76deb675372a">

- Manhattan is the most popular area, with W 20 St & 11 Ave as the most frequent station.

<img width="798" alt="Screenshot 2024-11-14 at 4 16 10 PM" src="https://github.com/user-attachments/assets/3b264168-9a46-4db5-82bf-07dd714fc1cf">

- Sunday is the most popular day overall, with Wednesday being the peak day for male users and Saturday for female users.

<img width="797" alt="Screenshot 2024-11-14 at 4 16 23 PM" src="https://github.com/user-attachments/assets/99ef2ef8-6b07-4f31-bf67-9fa6ce849785">

      
# Actions
- Offer targeted promotions or discounts to specific user groups (e.g., millennials, first-time users) to increase usage.
- Use trip start and end data to identify high-demand areas for optimal station placement, improving convenience and reducing bike shortages.
- Adjust fleet availability and pricing strategies during peak usage times to better serve users.
- Continuously monitor and update user segments to refine service offerings and adjust for seasonal trends or behavioral changes.

# Summary
This project provides useful insights into how CitiBike users behave and how bike trips are made. Looking ahead, we could improve the analysis by including weather data (like temperature or rain) and the time of day. These factors could give us a better understanding of how weather affects when and how long people ride bikes. For example, we could see if more people use bikes when it's warmer or if rainy days lead to fewer trips. Similarly, looking at what times of day people use bikes the most could help manage bike availability, making sure more bikes are ready during busy periods like rush hours or evenings.

# Features
- Trip Duration Bands: Categorizes trip durations into predefined time ranges for easy analysis.
- Dynamic User Grouping: Allows for dynamic segmentation of users based on Gender, Generational Cohorts, or User Type.
- Interactive Dashboards: Built with Tableau to provide interactive visualizations of the data, with the ability to toggle between different segments for deeper analysis.
- Calculated Fields: Used to categorize data (e.g., Trip Duration, User Groups) into meaningful bands for easier comparison.
Tools & Technologies
- Tableau: Used for creating interactive dashboards and visualizations.
- Python: Used for data processing, cleaning, and analysis. Calculations and data transformations were performed using Python libraries such as Pandas.
- CitiBike Dataset: Obtained from Kaggle (https://citibikenyc.com/system-data), the dataset contains trip-level data for CitiBike users, including information on trip duration, start and end stations, user type, and more. 
