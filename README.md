### Pizza Sales Analysis Report
# Overview
This project involves analyzing pizza sales data using Excel to derive actionable insights through pivot tables, charts, and data cleaning techniques.

## Questions and Tasks
- Pivot Analysis and Charting
- Total Net Profit by Channel

- Create a pivot table showing total net profit for each channel.
- Visualize the results using a bar chart.
- Average Impressions and Clicks by Audience

- Create a pivot table showing average impressions and clicks grouped by audience.
- Visualize the results using a stacked bar chart.
- Total Clicks Per Campaign for Facebook and Instagram

- Filter the data for Facebook and Instagram campaigns.
- Create a pivot table for total clicks per campaign.
- Visualize the results using a pie chart.
- Language Slicer Integration

-- Connect a language slicer to the bar chart, stacked bar chart, and pie chart.
-- Highlight Top Months by Average Engagement Score

-- Use conditional formatting to highlight the top two performing months for each language based on the average engagement score.
-- Monthly ROI for Product Launch Campaigns

-- Calculate monthly ROI as:
-- Monthly ROI = Total Net Profit per Month / Total Cost per Month.
-- Use a calculated field in a pivot table.
-- Visualize the results using a line chart.
-- BONUS Tasks

## Data Cleaning

-- Company and Location Separation:
-- Split the companylocation field into two separate columns: Company and Location.
-- Clean campaign_goal:
-- Use the SUBSTITUTE() function to clean the campaign_goal column with nested substitutions.
-- Clean duration:
-- Separate the numeric value and the days text from the duration column into distinct fields.
-- Clean acquisition cost:
-- Extract numeric values from USD in the acquisition cost column, ensuring the resulting field is purely numeric.

## Net Profit Calculation

-- Create a new column for net_profit:
-- Net Profit = ROI * Acquisition Cost.

## Data Consolidation

-- Bring the date, channel_used, and customer_segment columns from the Data2 sheet to the Data1 sheet for analysis.
-- Tools and Techniques
-- Pivot Tables: For summarizing and analyzing data.
-- Conditional Formatting: For highlighting key insights.
-- Charts: Bar, stacked bar, pie, and line charts for visualization.
## Data Cleaning Functions:
-- SUBSTITUTE() for cleaning textual data.
-- Text-to-Columns and formulas for splitting fields.
### Results
-- The analysis will help uncover trends in sales channels, audience behavior, campaign effectiveness, and ROI. By integrating charts, slicers, and cleaned data, this report provides a comprehensive view of pizza sales performance.
