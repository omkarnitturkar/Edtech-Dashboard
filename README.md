# EdTech Recorded Lectures Dashboard

Dashboard Link : [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTdiMGFiNzctZDU3My00ZWUzLWIyZDgtNGViMWQ4N2M1MjAwIiwidCI6ImI4ZTA5ODljLTk5MmQtNGY2ZC04ZWFiLTIxMTI0ZTMyYzk0OCJ9)

### Problem Statement
This project aims to analyze data from various EdTech platforms to help an EdTech startup expand its recorded lecture offerings. The goal is to provide strategic insights through a Power BI dashboard, focusing on category-wise analysis to optimize course offerings and viewer engagement.

### Data Analysis Objectives
The dashboard provides insights into the following areas:

1. **Course Distribution by Category & Sub-Category**
   - Identify trends in course distribution to help the startup determine strategic course launches.
   - Count the number of courses per category and sub-category.

2. **Average Views Analysis**
   - Calculate the average number of views for each category, sub-category, and language to understand engagement patterns.

3. **Popular Skills by Category**
   - Identify the most commonly taught skills to ensure course offerings align with current job market demands.

4. **Language Distribution**
   - Analyze the distribution of different languages in which courses are created.

5. **Language Preferences for Top 5 Categories**
   - Determine preferred languages for each category based on viewer preferences to optimize content accessibility.

6. **Impact of Subtitles on Viewership**
   - Investigate whether the availability of subtitles influences the number of views for courses.


7. **Top Instructors by Category & Sub-Category**
   - Identify the top three instructors in each category and sub-category based on ratings to highlight educators producing high-quality content.

8. **Course Duration vs. Views**
   - Analyze the relationship between course duration and viewership to understand optimal course length.
   - Courses with fixed monthly hours (60 hours per month) and flexible schedules (200 hours) are considered.

9. **Impact of Skill Variety on Viewership**
   - Investigate whether the number of different skills offered within each category and sub-category affects viewer engagement.

### Popular Skills by Category
![Popular Skills](https://github.com/omkarnitturkar/Edtech-Dashboard/blob/main/Skills.JPG)

### Impact of Subtitles on Viewership
![Impact of Subtitles](https://github.com/omkarnitturkar/Edtech-Dashboard/blob/main/Viewership.JPG)

### Dashboard Features
- **Interactive Visuals**: Users can filter data by category, sub-category, language, and other key parameters.
- **Static Insights**: Top instructors for each category and sub-category are displayed as static visualizations.
- **Engagement Metrics**: Viewership trends based on language, subtitles, and course duration.

### Technologies Used
- **Power BI** for data visualization
- **Python (Pandas, NumPy)** for data cleaning and preprocessing
- **SQL** for querying and data extraction

### How to Use
1. Clone this repository:  
   ```bash
   git clone https://github.com/omkarnitturkar/edtech-dashboard.git
   ```
2. Open the Power BI file (`.pbix`) in Power BI Desktop.
3. Explore different visualizations and insights using filters and interactive elements.

### Data Source
The dataset used for this analysis is sourced from [Kaggle - Online Courses Dataset](https://www.kaggle.com/datasets/khaledatef1/online-courses)
