# PwC-Call-Center-Dataset---Power-BI

PwC Switzerland Call Center Dataset – Power BI Project

STEPS INVOLVED

1.	Importing the excel workbook into Power BI.<br>
2.	Transforming the dataset
3.	Handling null values
•	Replacing the columns containing null values with 0 (Speed of answer in seconds, AvgTalkDuration and Satisfaction rating)
4.	Data Cleaning
•	Renaming the column ‘Resolved’ to ‘Resolved (Y/N)<br>
•	Changing the datatype of column ‘Time’ from Date/Time to Time.<br>
•	For the ‘AvgTalkDuration’ column, we first change the datatype of column ‘Time’ from Date/Time to Time. Then we separate the minutes and seconds each to different columns and we merge the minutes and seconds column together. The merged column will be renamed as ‘Talk Duration’. 
5.	Save and apply to load the dataset into Power BI.
6.	Create a dashboard in Power BI for Claire that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset.
            Possible KPIs include (to get you started, but not limited to):
•	Overall customer satisfaction
•	Total Calls
•	Overall calls answered/abandoned
•	Percentage of calls answered/abandoned
•	Overall calls resolved/not resolved
•	Percentage of calls resolved/not resolved
•	Calls by time
•	Average speed of answer
•	Total number of Agents
•	Agent with highest satisfaction rating/least satisfaction rating
•	Agent with most calls answered/abandoned
•	Total number of Topics 
•	Topic with the highest calls/least calls
•	Agent’s performance quadrant -> average handle time (talk duration) vs calls answered
