# YouTube Data Analysis Power BI Project

This project analyzes a YouTube dataset using Power BI to uncover insights that help content creators and marketers optimize their content strategies. By examining viewer engagement and video performance metrics, the project aims to guide data-driven decisions to enhance viewer interaction and boost content performance.

---

## Overview

This project leverages data from YouTube to uncover valuable insights by analyzing engagement metrics and video attributes. The objective is to assist content creators in improving their content strategies, driving higher viewer engagement, and optimizing their overall channel performance.

---

## Objectives

- **Identify patterns and trends** within the YouTube dataset to understand how various video attributes influence viewer engagement.
- **Answer key questions** related to viewer behavior, such as: What type of content is most engaging? Which channel types have the highest interaction rates?
- **Assist content creators** in enhancing their content strategy based on data-driven insights to increase views, subscribers, and overall interaction.

---

## Data Sources

- **YouTube Dataset**: Extracted using the YouTube API.
- The dataset is then processed and transformed (ETL) before being loaded into Power BI for analysis.

---

## Key Deliverables

### Data Exploration & Visualization

1. **Maximum Uploads**: 
   - **Card Visual**: Displays the maximum number of uploads on a channel.

2. **Minimum View Ranks**: 
   - **Card Visual**: Showcases the channel with the minimum view rank.

3. **Average Views (Last 30 Days)**: 
   - **Card Visual**: Displays the average number of views for videos in the last 30 days.

4. **Maximum Uploads Line Chart**: 
   - **Line Chart**: Highlights videos with more than 200,000 uploads, showing trends over time.

5. **Channel Type & Rank Radar Chart**: 
   - **Radar Chart**: Visualizes the relationship between different channel types and their ranks.

6. **Category-wise Subscribers Packed Bubble Chart**: 
   - **Packed Bubble Chart**: Displays the number of subscribers for each category, allowing for easy comparison.

7. **Views per Subscriber Table**: 
   - **Table Visual**: Visualizes the relationship between channel type and the views per subscriber for better content targeting.

### Data Calculations

1. **Calculated Column**: 
   - "Viewed by Subscriber" for views-per-subscriber analysis, providing deeper insights into content performance relative to subscriber base.

2. **Measure**: 
   - Total number of uploads across channels.

3. **Decomposition Tree**: 
   - Visualizes categories based on rank to explore which types of content are performing best.

---

## Report Development

- **Report Formatting**: Ensures consistent styling, headings, and logos for an aesthetically pleasing and user-friendly report.
- **Navigation**: Includes a blank navigation button for seamless page transitions, enhancing user experience.
- **Dashboard Creation**: Develop a high-level summary dashboard that showcases key visuals and metrics.

---

## Deployment

- **Publish**: The report is published to the Power BI Service for easy access and sharing with stakeholders.
- **Dashboard Creation**: The dashboard summarizes key insights and is shared for decision-making purposes.

---

## Tools & Technologies

- **Power BI Desktop**: Used for data analysis, visualizations, and report creation.
- **YouTube API**: Extracts the data from YouTube for analysis.
- **Power BI Service**: For deploying and sharing the report online.
  
---

## Note

This project adheres to YouTube's terms of service and data privacy guidelines.

---

## Getting Started

### 1. **Data Acquisition**

Obtain the YouTube dataset by querying the YouTube API for relevant engagement metrics, such as views, subscribers, video uploads, and more.

### 2. **Data Preparation**

Cleanse, transform, and load the data into Power BI. This step includes removing duplicates, handling missing values, and formatting data for visualization.

### 3. **Data Analysis & Visualization**

- Create various visualizations (e.g., card visuals, line charts, radar charts) to explore key metrics such as uploads, views, and subscribers.
- Perform data analysis to uncover patterns and insights about viewer behavior, content performance, and channel types.

### 4. **Report Development**

Design and format the Power BI report, ensuring a clean, consistent, and easily navigable layout. Add interactive features like slicers for better user experience.

### 5. **Deployment**

Publish the report to Power BI Service and create a dashboard for high-level insights and easy sharing with stakeholders.

---

## Conclusion

This project demonstrates the power of data-driven decision-making for YouTube content creators and marketers. By leveraging Power BI, the project uncovers valuable insights from the YouTube dataset, empowering creators to optimize their content strategies, improve engagement, and grow their audience. The interactive and visually appealing dashboard makes it easy to explore trends and metrics, ultimately helping creators make informed decisions based on actionable insights.

Feel free to explore the project and customize it for your specific use cases!

