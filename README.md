# Google-Capstone-Project-

**Bellabeat FitTracker analysis**

![female-runner-running-at-summer-park-trail-healthy-royalty-free-image-1591373138](https://user-images.githubusercontent.com/123582571/216449970-e4ecd244-65be-4fe7-9367-d62c0b36a34c.jpg)

:golf: **Company background**

Bellabeat is a high-tech company founded in 2013 that manufactures health-focused smart products which inspires woman around the world. Bellabeat empower women with knowledge about their own health and habits by collecting data on activity, sleep, stress and reproductive health.

The case study is done in order to reveal more opportunities for Bellabeat’s growth by getting insights on how people using their smart devices. By doing this, the company could figure out the trend and make adjustment on marketing strategies to promote growth.

:soccer:**Ask Phase**

:scroll:To identify the trend of how consumers using smart devices and provide recommendations to the marketing team in order to apply the insight into latest marketing strategies.

:scroll:Who are the stakeholders:

1)Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer

2)Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team

3)Bellabeat marketing analytics team

:basketball: **Prepare Phase**

:scroll: Data used and information

The data that we used in the analysis process was a public dataset, Fitbit Fitness Tracker Data(CC0: Public Domain, dataset made available through Mobius). This Kaggle data set contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes information about daily activity, steps, and heart rate that can be used to explore users’ habit.

**We will use R in order to explore, analyze and visualize the data to find out the trend of how consumers use their smart devices. We also use SQL queries on the data frame by loading sqldf() .**

:tennis:**Cleaning Data Process**

We process the data and clean some of the data to ease the process of analysis. The cleaning processes are:

* *dropping NA values*

* *drop duplicates*

* *naming some of the variables* and 

* *standardize the format*.

The detailed data cleaning process could refer to [here](https://github.com/yijing917/Google-Capstone-Project-/blob/main/bellabeat-project-google-data-analytics.ipynb). 


:ping_pong: **Analyse Phase** 

We will analyse the user trend of fitbits and identify what are the keys could be used as the marketing strategy for Bellabeat.

These are some of the questions we could brainstorm in order to identify the trend:

* *How often the users wear smart devices? Group the users on usage frequency?*

* *What are the lifestyles of the users? Active or moderate or sedentary? ( since the demographic data are not provided, we could group the users by average steps)*

* *Most active hours ? the calories graph – to identify the active hours of users*

* *Correlation between steps/calories/ sleeptime?*

The detailed analysis could refer to [here](https://github.com/yijing917/Google-Capstone-Project-/blob/main/bellabeat-project-google-data-analytics.ipynb). 


:bowling:**Act Phase**

**Conclusion**

In order for us to help Bellabeat's team to improve their marketing strategies, I would recommend to collect more data in details such as demographic data since we have a specific target customers - young women adult. The current dataset used a small sample sizes which might not be as accurate or could be highly biased. Moreover, if we manage to collect the latest data it would be easier to identify the current usage trend and we could discuss further on the marketing strategies.

Based on the findings,

How often users use smart device Findings= 50% of the users are using their device in between 21-31 days. We could promote the long last batteries of our device as the big advantage of using our tracker. However more analysis needed to be done on our own tracking data so we could determine what is the usage rate among customers.

User activeness based on calories= Findings= 67% of users in the dataset consumed at least 2000 calories per day. We could improve our device by sending notification to promote active lifestyle. If we could create any programme that allow user to calculate their own BMR rate and how much calories they should burn to be in active lifestyle, it would be really useful especially for users who are in active lifestyle or starting diet plan.

That's the end of my first project.:trophy:

Thank you!
