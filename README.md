# Capital-Bikeshare-EDA-and-ML-linear-regression-model-
Bikeshare company Data analysis
Report on User Behavior and Demand Prediction for Capital Bikeshare

TECHNOLOGIES USED:
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import matplotlib.patches as mpatches  
import seaborn as sns
from scipy import stats
import datetime as datetime
sklearn
LinearRegression


Overview of Capital Bikeshare
Capital Bikeshare operates across the Metro DC area with over 7,000 bikes and 700+ stations in 8 jurisdictions, including Washington, DC; Arlington, VA; Alexandria, VA; Montgomery, MD; Prince George's County, MD; Fairfax County, VA; the City of Fairfax, VA; and the City of Falls Church, VA. Their mission is to expand bikeshare access, create safer and healthier communities, and celebrate the diversity of the region.

The organization offers $5 annual memberships to qualifying residents through the "Capital Bikeshare for All" program, which supports those on federal or state assistance programs such as SNAP, WIC, TANF, and Medicaid, among others. Members enjoy unlimited 60-minute rides on classic and e-bikes, with nominal per-minute charges for extended trips.

Data Insights and Analysis: 

1. Overall Trends
   
The total rides in the past year have shown consistent growth, except in 2021, which experienced a significant dip in demand, likely due to the COVID-19 pandemic. However, by the end of 2021, demand began to recover as people resumed outdoor activities.
2023 has been a particularly strong year for ridership, reflecting increased public engagement with the bikeshare program.

2. User Behavior by Membership Type

Members vs. Casual Users:
Members account for 60% of total rides, while casual users contribute nearly 40%. This distribution is favorable for the company as it indicates a strong base of repeat users.
Riding Patterns:
Members: Ride frequency peaks during morning (6 AM–8 AM) and evening (4 PM–6 PM) commute hours, aligning with work schedules. Weekday ridership is notably higher for members.
Casual Users: Ride frequency gradually increases throughout the day, with peaks around midday, reflecting more leisurely or tourist-driven usage.

3. Seasonal Trends

Peak Seasons: Demand is highest in summer and autumn, particularly in the afternoons, when people are more likely to ride.
Winter: Ridership significantly declines during winter, likely due to unfavorable weather conditions.

4. Weather Influence on Ridership

Preferred Conditions:
Most rides occur under clear or partly cloudy skies, suggesting that good weather significantly influences bike usage.
Interestingly, ridership persists, albeit slightly lower, during light rain.
Low Demand Scenarios:
Very few rides are recorded during slight or heavy snowfall, likely due to freezing temperatures and safety concerns.

5. Temperature Trends

Demand correlates with temperature:
Winter & Spring: Low ridership during colder months.
Spring & Autumn: Peaks on warm days, as these seasons provide pleasant weather conditions for cycling.
Summer: Surprisingly, demand slightly dips, possibly due to extreme heat or vacation-related absences.
Conclusions
Consistent Growth: Despite challenges in 2021, Capital Bikeshare has shown strong recovery and growth, particularly in 2023.
Targeted Engagement: Efforts to attract casual users, while maintaining a strong membership base, have created a balanced user profile.
Seasonal Adjustments: Marketing campaigns and promotions during summer and autumn could capitalize on peak ridership seasons, while incentives during winter may help mitigate lower demand.
Weather-Responsive Strategies: Ensuring rider safety and comfort in less favorable weather conditions (e.g., through better equipment or promotions) could further enhance user experience and ridership.
Further Exploration: Understanding why summer ridership slightly dips could provide valuable insights for targeted engagement strategies.
