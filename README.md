# Overview
Welcome to my analysis of the data job market, focusing on data analyst roles in India. This project was created out of a desire to navigate and understand the job market and apply Python skills more effectively. It delves into the top-paying and in-demand skills to help find optimal job opportunities for data analysts.

The data sourced from Luke Barousse's Python Course provides a foundation for my analysis, containing detailed information on job titles, salaries, locations, and essential skills. Through a series of Python scripts, I explore key questions such as the most demanded skills, salary trends, and the intersection of demand and salary in data analytics.

# The Questions
Below are the questions I want to answer in my project:

1) What skills are most in demand for the top 3 most popular data roles?
2) How are in-demand skills trending for Data Analysts?
3) How well do jobs and skills pay for Data Analysts?
4) What are the optimal skills for data analysts to learn? (High Demand AND High Paying)

# Tools I Used
For my deep dive into the data analyst job market, I harnessed the power of several key tools:

**Python**: The backbone of my analysis, allowing me to analyze the data and find critical insights. I also used the following Python libraries:
**Pandas Library**: This was used to analyze the data.

**Matplotlib Library**: I visualized the data.

**Seaborn Library**: Helped me create more advanced visuals.

**Jupyter Notebooks**: The tool I used to run my Python scripts which let me easily include my notes and analysis.

**Git & GitHub:** Essential for version control and sharing my Python code and analysis, ensuring collaboration and project tracking.

# Data Preparation and Cleanup
This section outlines the steps taken to prepare the data for analysis, ensuring accuracy and usability.

**Import & Clean Up Data**
I start by importing necessary libraries and loading the dataset, followed by initial data cleaning tasks to ensure data quality.

**Filter India Jobs**
To focus my analysis on the Indian job market, I apply filters to the dataset, narrowing it down to roles based in India.

# The Analysis & Findings
Jupyter notebook for this project aimed at investigating specific aspects of the data job market. Here’s how I approached each question:

**1. What are the most demanded skills for the top 3 most popular data roles?**
To find the most demanded skills for the top 3 most popular data roles. I filtered out those positions by which ones were the most popular and got the top 5 skills for these top 3 roles. This query highlights the most popular job titles and their top skills, showing which skills I should pay attention to depending on the role I'm targeting. 

**Findings**

Data Engineers require more specialized technical skills (AWS, Azure, Spark) compared to Data Analysts and Data Scientists who are expected to be proficient in more general data management and analysis tools (Excel, Tableau).

Python is a versatile skill, highly demanded across all three roles, but most prominently for Data Scientists (70%) and Data Engineers (68%).

**2. How are in-demand skills trending for Data Analysts?**
To find how skills are trending in 2023 for Data Analysts, I filtered data analyst positions and grouped the skills by the month of the job postings. This got me the top 5 skills of data analysts by month, showing how popular skills were throughout 2023.

**Findings**

SQL remains the most consistently demanded skill throughout the year while Python & Excel compete for the second spot throughout the Year.
Tableau remains ahead of Power BI for the Data Analytics job role.

**3. How well do jobs and skills pay for Data Analysts?**
To identify the highest-paying roles and skills, I only got jobs in India and looked at their median salary. But first I looked at the salary distributions of common data jobs like Data Scientist, Data Engineer, and Data Analyst, to get an idea of which jobs are paid the most.

**Findings**

There's a significant variation in salary ranges across different job titles. Senior Data Engineer positions tend to have the highest salary potential, indicating the high value placed on advanced data skills and experience in the industry.

**Highest Paid & Most Demanded Skills for Data Analysts**

The top graph shows specialized technical skills like postgresql, pyspark and Gitlab are associated with higher salaries, some reaching up to $200K, suggesting that advanced technical proficiency can increase earning potential.

**4. What are the most optimal skills to learn for Data Analysts?**
To identify the most optimal skills to learn ( the ones that are the highest paid and highest in demand) I calculated the percent of skill demand and the median salary of these skills. To easily identify which are the most optimal skills to learn.

**Findings**

The skill Mongodb appears to have the highest median salary of nearly $97K, despite being less common in job postings. This suggests a high value placed on specialized skills within the data analyst profession.
More commonly required skills like Excel and SQL have a large presence in job listings but lower median salaries compared to specialized skills like PowerBI and Tableau, which not only have higher salaries but are also moderately prevalent in job listings.

# What I Learned Throughout this project
I deepened my understanding of the data analyst job market and enhanced my technical skills in Python, especially in data manipulation and visualization. Here are a few specific things I learned:

**Advanced Python Usage:** Utilizing libraries such as Pandas for data manipulation, Seaborn and Matplotlib for data visualization, and other libraries helped me perform complex data analysis tasks more efficiently.

**Data Cleaning Importance:** I learned that thorough data cleaning and preparation are crucial before any analysis can be conducted, ensuring the accuracy of insights derived from the data.

**Strategic Skill Analysis:** The project emphasized the importance of aligning one's skills with market demand. Understanding the relationship between skill demand, salary, and job availability allows for more strategic career planning in the tech industry.

**Insights**

**Skill Demand and Salary Correlation:** There is a clear correlation between the demand for specific skills and the salaries these skills command. Advanced and specialized skills like Python and Oracle often lead to higher salaries.

**Market Trends**: There are changing trends in skill demand, highlighting the dynamic nature of the data job market. Keeping up with these trends is essential for career growth in data analytics.

**Economic Value of Skills:** Understanding which skills are both in-demand and well-compensated can guide data analysts in prioritizing learning to maximize their economic returns.

**Challenges I Faced**

This project was not without its challenges, but it provided good learning opportunities:

**Data Inconsistencies:** Handling missing or inconsistent data entries requires careful consideration and thorough data-cleaning techniques to ensure the integrity of the analysis.

**Complex Data Visualization:** Designing effective visual representations of complex datasets was challenging but critical for conveying insights clearly and compellingly.

**Balancing Breadth and Depth:** Deciding how deeply to dive into each analysis while maintaining a broad overview of the data landscape required constant balancing to ensure comprehensive coverage without getting lost in details.

# Conclusion

This exploration into the data analyst job market has been incredibly informative, highlighting the critical skills and trends that shape this evolving field. The insights I got enhance my understanding and provide actionable guidance for anyone looking to advance their career in data analytics. As the market continues to change, ongoing analysis will be essential to stay ahead in data analytics. This project is a good foundation for future explorations and underscores the importance of continuous learning and adaptation in the data field.






