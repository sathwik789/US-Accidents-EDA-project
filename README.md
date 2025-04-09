🚗 US Accidents (2016–2023) - Exploratory Data Analysis
This project presents an in-depth Exploratory Data Analysis (EDA) on the US Accidents dataset (2016–2023), which contains over 7.7 million traffic accident records from across the United States. The main objective of this project is to uncover meaningful trends, patterns, and 7 actionable insights that can help in understanding accident causes, high-risk conditions, and strategies for safer roads.

Using Python and popular data analysis libraries like NumPy, Pandas, Matplotlib, and Seaborn, this project explores various dimensions of the dataset including time, location, weather conditions, and severity levels.

📊 Key Highlights:
Cleaned and preprocessed a massive real-world dataset.

Performed univariate and multivariate analysis to study factors contributing to accidents.

Created insightful visualizations to communicate findings effectively.

Discovered 7 actionable insights to aid city planners, traffic authorities, and policymakers.

📂 About the Dataset
📄 Description
This is a countrywide car accident dataset that spans 49 states in the USA, with data collected between February 2016 and March 2023. The dataset is one of the largest open-source resources for traffic incidents in the United States.

Accident records were gathered through multiple streaming APIs that provide real-time data captured by various sources.

Key Insights from Traffic Accident Data Analysis
🚦 Traffic Signal Impact
85% of accidents occurred in areas without traffic signals, indicating a strong correlation between lack of traffic regulation and accident frequency.

This suggests poor adherence to traffic rules in unsignaled areas, highlighting the need for better infrastructure and enforcement.

🏙️ City-wise Accident Distribution
Over 90% of cities reported fewer than 1000 annual accidents.

Only ~9% (1,215 cities) recorded more than 1000 accidents annually, implying a concentrated issue in specific urban areas.

Notably, 1,000+ cities recorded only 1 accident over 7 years, suggesting the need to verify or investigate data consistency or sparsity.

⏰ Time-Based Accident Patterns
Hours of the Day:
Morning peak (6 AM – 8 AM) and evening hours (2 PM – 6 PM) show the highest accident rates, aligning with commuting times.

Late night to early morning (12 AM – 3 AM) shows the lowest accident frequency, likely due to reduced road activity.

Day of the Week:
Weekdays (Mon–Fri) see higher accident rates, mainly during commute hours.

Weekends (Sat–Sun) show a decline, with midday (11 AM – 3 PM) seeing relatively more incidents, possibly due to leisure travel.

📅 Month-Wise Accident Trends
Peak accident months: November, December, January, likely due to winter conditions like snowfall and low visibility.

Safer months: March to July, showing significantly lower accident rates.

📈 Yearly Trend Analysis
Accidents have steadily increased from 2016 to 2022, peaking at 1.76 million in 2022.

2023 shows a drop, but the data is only recorded till March, hence incomplete.

🚨 Severity of Accidents
Severity Level 2 (moderate impact) is the most common.

Severity Level 3 accounts for ~17% of accidents, while severe (Level 4) accidents make up only 2.65%.

Minor (Level 1) incidents are less than 1%, suggesting most accidents moderately disrupt traffic.

📡 Data Source Reliability
Data is gathered from three sources via real-time traffic APIs.

Source 1 and Source 2 provide the majority of records, while Source 3 contributes the least.

🌍 Geographical Insights (Latitude & Longitude)
Most accidents occur in the coastal and urban regions of the East and West US.

Central US shows fewer accidents, likely due to lower population density and less traffic volume.

🌡️ Temperature vs. Accident Frequency
Majority of accidents occurred between 0°C to 25°C, consistent with winter season trends noted in month-wise analysis.

Winter-related hazards like icy roads and reduced traction contribute significantly to these accidents.

🧹 Data Cleaning Approach
Columns with greater than 5% missing values were removed to ensure analysis is clean and reliable.

This preprocessing step improves model accuracy and interpretability.
U.S. and State Departments of Transportation (DOTs)
Law enforcement agencies
Traffic cameras
Roadside traffic sensors
The dataset currently includes approximately 7.7 million accident records, making it an excellent foundation for both exploratory and predictive analysis.
