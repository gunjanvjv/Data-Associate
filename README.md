# Data-Associate
OBJECTIVE
The objective of this assignment is to evaluate your ability to analyze raw data and provide insights from it. You will be required to clean, analyze and visualize associate performance data and provide actionable insights .
DATASET
So the given dataset has three 3 sheets for every associate having 
Date: The date of lead generation activities.
Leads_Generated: The number of leads generated by each employee on a specific date.
Time_Spent (in mins): The total time spent by each employee on lead generation activities on a specific date. The unit of measurement is minutes
Step 1- All the three sheets are merged together and created a new row “Associate”.
Step 2- In this step data is cleaned all the null values and the missing values are removed and created a cleaned dataset
Step 3 – In the this step Data Exploration is done and presented suitable Key Performance Indicator for each Associate 
1.	Average Leads Generated per day
2.	Average Time Spent per day.
3.	Conversion Rate (Leads Generated per hour).
Step 4 – Data is visualized and analyzed by creating different visualizations (like bar chart,scatter chart, histogram etc)
The analysis report can be seen using this link where all these are done along with the code for better understanding .

Answers to the following questions:
1.	What is the total number of leads generated by Each Associate.
                 Total number of leads generated by each associate:
           Associate         No_of_Leads
    0     Associate ABC           48
1	   Associate XYZ           41
    2     Associlate KLM          107

2.	 What is the total number of leaves taken by each associate (considering Saturday and Sunday as holidays)?
        Total number of holidays taken by each associate:
           Associate         No_of_Holidays
    0     Associate ABC           2
1	   Associate XYZ           1
2	   Associlate KLM          12

3.	What is the average number of leads generated by each associate?

           Average number of leads generated by each associate:
                 Associate    No_of_Leads
         0   Associate ABC      6.541667
         1   Associate XYZ     10.853659
         2   Associlate KLM     9.850467
4.	Which associate has been the most consistent in lead generation?

         Most consistent associate in lead generation:
           Associate      Associate XYZ
           No_of_Leads         2.555005
  5. Do you remove missing values from the data-set for analysis? Provide rationale for    your answer.
    Yes, there were missing values in the dataset.
    Initial shape of the dataset was (267 , 4)
    From this we can see that there are null columns in No_of_Leads and Time_Spent
 After cleaning the data we can see that all the null values are removed and we got the cleaned dataset and the shape is (196,4)



