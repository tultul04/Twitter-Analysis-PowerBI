# Twitter-Analysis-PowerBI
A data visualization project built using Power BI to analyze Twitter data and extract insights such as engagement trends, media performance, and tweet behavior under custom conditions.
#📊 Project Overview
This dashboard helps uncover patterns and performance metrics from Twitter data. It includes:
Total and average engagement metrics
Time-based tweet performance analysis
Media views vs. media engagement correlation
Tweet trend lines with detailed filtering
Conditional visual display based on custom logic

#🛠️ Tools Used
Power BI
DAX (Data Analysis Expressions)
Power Query Editor
#✅ Key Tasks Implemented
🔹 Task 1: Time-Filtered Impressions & Engagement
Goal: Show a visual of average engagement rate and total impressions
Conditions:
Tweets between 01-01-2020 and 30-06-2020
Impressions ≥ 100
Likes = 0
Visible only between 3 PM – 5 PM IST

🔹 Task 2: Scatter Chart – Media Engagements vs Views
Goal: Visualize the relationship between media views and engagements
Conditions:
Replies > 10
Engagement Rate > 5% (highlighted)
Tweet word count > 50
Tweet date is an odd number
Chart visible only between 6 PM – 11 PM IST

🔹 Task 3: Monthly Engagement Trend
Goal: Line chart of average engagement rate by month
Conditions:
Separate lines: tweets with vs without media
Displayed only between 7 AM – 11 AM and 3 PM – 5 PM IST
Even-numbered tweet engagements
Odd tweet dates
Character count > 20
Tweets without the letter 'C'

#🚀 How to Run
Clone the repo
Open TwitterAnalytics.pbix in Power BI Desktop
Ensure dataset is connected or imported
Interact with the filters and visuals

