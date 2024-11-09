Call Centre Trend Analysis Project - PwC Internship Program

Overview

As part of my internship program with PwC, I conducted a comprehensive Call Centre Trend Analysis for the period from January 1, 2021, to March 31, 2021. This project involved utilizing Power BI Desktop to analyze key performance indicators (KPIs), call distribution by topic, agent efficiency, and overall customer satisfaction. The analysis was focused on understanding call trends, agent performance, and the overall efficiency of the call center.

Objectives

1.Identify the distribution of resolved calls by topic.

2.Analyze the average handle time and response time per agent.

3.Assess customer satisfaction ratings by topic and by agent.

4.Examine call volume trends throughout the day to optimize staffing and scheduling.

Key Insights

1. Resolved Calls Distribution by Topic
   
 - The primary topics of customer interactions included Streaming, Payment-related issues, Technical Support, Admin Support, and Contract-related concerns.
 
 - The highest volume of resolved calls was for Streaming issues, followed closely by Payment-related and Technical Support queries.
 
2. Total Satisfaction Rating by Agent
   
 - The analysis showcased agents' performance in terms of customer satisfaction scores.
 
 - Agents like Joe and Martha maintained high satisfaction ratings above 70%, highlighting their effective handling of customer inquiries.
 
3. Total Satisfaction Rating by Topic
   
 - Streaming topics received the highest customer satisfaction ratings, averaging 20.89%, followed by Payment-related and Technical Support topics.

4. Agent Efficiency Metrics
   
 - The project assessed the Average Handle Time (AHT) and Average Response Time per agent, which are crucial in determining overall agent productivity and call center efficiency.
 - Top-performing agents demonstrated balanced response and handle times, contributing to higher satisfaction ratings.

5. Total Resolves by Hour of the Day
   
 - Peak performance times were identified to guide future call scheduling and optimize response efficiency during high-demand hours.
 - The highest call resolve rates were observed during 11:00 AM and 3:00 PM periods.

6. Overall Call Center Performance
   
 - Total Calls Handled: 4,054
 - Total Resolved Calls: 3,646
 - Total Abandoned Calls: 1,354
 - Average Processing Speed: Approximately 7.15 minutes per call.

7. Tools and Techniques Used
   
 - Power BI Desktop: Used for data visualization and dashboard creation to provide an interactive report on the call center’s KPIs.
 - Data Analytics: Applied data cleaning and analysis techniques to extract meaningful insights from large datasets.
 - Excel: Assisted in data preparation and cross-verification of metrics.

8. Dax query used

 -  Total Resolved 

       Total Resolved = CALCULATE(COUNTROWS('01 Call-Center-Dataset'),'01 Call-Center-Dataset'[Call Status]="Resolved")

 -  Total Abandoned 

       Total Abandoned = CALCULATE(COUNTROWS('01 Call-Center-Dataset'),'01 Call-Center-Dataset'[Call Status]="Abandoned")

8. Challenges and Solutions
   
 - Data Accuracy: Ensured data reliability by conducting cross-references between data sources.
 - Visualization Clarity: Maintained simplicity in dashboard design to make it user-friendly and easily interpretable.

9. Impact 

This analysis has laid the groundwork for future performance improvement initiatives. By identifying trends in call volume and agent productivity, the call center can strategically optimize resource allocation, enhance training programs, and improve customer service practices. The next phase includes refining predictive models to forecast call trends and further improve response strategies.

<img width="633" alt="image" src="https://github.com/user-attachments/assets/2144f684-f6bf-4a74-821d-46ebded468c2">


