
In this Project i am assuming the role of a Data Analyst for Accenture.

# INSTRUCTIONS:
You’ve been assigned to a new project and the first thing you must do is get up to speed with the business problem that this project is tackling, the requirements that need to be fulfilled as deliverables and the alignment of internal teams with the client.

You will be working within a large team at Accenture and there will be several people on your team doing different roles to make this project a success.

As a data analyst, it is imperative that you have a solid understanding of the project as quickly as possible. A data analyst sits between the business and the data, so it’s important that you have a deep understanding from both sides to provide insights. You need to use the client brief to:

Understand the client and business problem at hand.
Identify the requirements that need to be delivered for this project.
Identify which tasks you should focus on.
To make sure that you have understood the project, you will be tested on an outline of the business problem, the requirements and the delegation of tasks.


# Here is the background information on your task:
You have been given a set of data sets, all containing different columns and values, as well as a data model. A data model shows the relationships between all of the data sets, as well as any links that you can use to merge tables.

It is your job to use these data sets as well as the data model, to create your own data set that you can use to fulfill the requirements of this task. 

This task is essential because it is one of the specific requirements that the client has asked for, so we are relying on the data analyst to work with the data and create accurate, reliable insights that can be backed up during the final presentation.

As a data analyst, it is important that you work with both the business and the data. Now that you have gained the business understanding, it’s time to put your analysis skills to the test. 

The next step will be bringing the data set to life. A large component of being a data analyst, includes the ability to find relevant insights and ensure that they are clearly communicated to the business and client. These insights should be synthesized and placed in a presentation for the client that is engaging and easily understood. 

There is an art to selecting the correct visualizations for your presentation and it’s important that corresponding communications tell a powerful story. For this reason, the powerful tools of data visualization & storytelling will be key to this task. 

The analysis that you provide will play a key part in the fulfillment of this requirement, so you will play an important role in this project!


# DataSet Summary and Data Model:
User
 ID: Unique ID of the user (automatically generated) Name: Full name of user

 Email: Email address of user
Profile

 User ID: Unique ID of a user that exists in the User table Interests: Interests of the associated user

Age: Age of the associated user
Location
User ID: Unique ID of a user that exists in the User table Address: Full address of the user
Session

User ID: Unique ID of a user that exists in the User table
Device: Mobile device that they used for this session on the application
Duration: Amount of time in minutes that this user stayed active on the application during this session
Content

ID: Unique ID of the content that was uploaded (automatically generated) User ID: Unique ID of a user that exists in the User table

Type: A string detailing the type of content that was uploaded

Category: A string detailing the category that this content is relevant to URL: Link to the location where this content is stored
Reaction

Content ID: Unique ID of a piece of content that was uploaded

User ID: Unique ID of a user that exists in the User table who reacted to this piece of content Type: A string detailing the type of reaction this user gave

Datetime: The date and time of this reaction

 # ReactionTypes
Type: A string detailing the type of reaction this user gave

Sentiment: A string detailing whether this type of reaction is considered as positive, negative or neutral

Score: This is a number calculated by Social Buzz that quantifies how “popular” each reaction is. A reaction type with a higher score should be considered as a more popular reaction.

# Data Model:

![Screenshot (68)](https://user-images.githubusercontent.com/41531796/198848110-d85558d8-9f20-48f0-8e4d-240912efb1a2.png)



# BUSINESS TASK:
An audit of their big data practice
- Recommendations for a successful IPO
- An analysis of their content categories that highlights the top 5 categories with the
largest aggregate popularity


# Tasks to do
 - Extraction of sample data sets
- Merging of sample data set tables
- Loading of sample data sets into Accenture sandbox database
- Analysis of sample data sets with visualizations
- Full documentation of the process that we can guide them thro



# DATA ANALYSIS PROCESS:
Data Exploration and Data Cleaning
I loaded dataset into Excel to explore the data and check the quality of the data. 

I made cell values in content table, category column consistent by capitilizing the first letter

I Performed a left jon and merged reaction types table with Content table using TYPE as the matching column. 

I deleted unecessary columns for the purpose of this analysis.

I merged the Profit table with users table to eliminate redundancy

I changed and tranformed necessary data types.

# Data Modelling
Final Modelling
![SocialBuz](https://user-images.githubusercontent.com/41531796/198848393-2aa5bacb-e305-4a16-a367-804e731206a1.jpg)

# Data Analysis and Visualization


![AccentureportfolioSocialBuzz](https://user-images.githubusercontent.com/41531796/198848407-e2477677-6f90-4950-9930-bb231ea7fbf6.png)


# INSIGHTS:
From your data we found that you had a total of 17 unique categories of posts across your sample dataset. This includes things such as Technology, Food, Science etc

An average of almost 48 mins is spent by users per day.

From our analysis you can see that the top 5 most popular categories of posts were Animals,Science, Healthy Eating, Technology and Food in descending order.

Animal had an aggregate popularity score of almost 67,000. It is very interesting to see both Animal and Science within the top 5, it really shows what people enjoy consuming as content.  But also interesting to see Healthy Eating and Food as well. Clearly users in Social Buzz favor "real-life and Science related" contents on this platform. 

As well as this, there was 1702 posts from just the Animal category alone! People obviously really love Animals!

The most common month for users to post within was May and January.

# RECOMMENDATIONS
We Recommend Social Buzz Marketing Team to schedule a marketing Plan targetting Animal Lovers and generally target audience from the Top Categories.



