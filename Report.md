# Feedback Analysis for Intel course

## Introduction
The analysis will focus on the feedback data collected from participants of a session, aiming to extract insights and identify patterns related to the participants' perceptions and satisfaction levels.

## Dataset overview

The dataset contains feedback responses from participants of a session. It includes several columns:

**Timestamp:** The date and time when the feedback was submitted.

**Name of the Participant:** The name of the participant who provided the feedback.

**Email ID:** The email address of the participant.

**Branch:** The branch of study of the participant.

**Semester:** The current semester of the participant.

**Resource Person of the session:** The resource person for the session.

**Ratings:** There are multiple columns related to ratings provided by the participants, covering the overall quality and relevance of the course content, the effectiveness of training methods and delivery style, the resource person's knowledge and expertise, the relevance and applicability to real-world industry scenarios, and the overall organization of the session.


## Exploratory Data Analysis (EDA)

- **Resource Person-wise Distribution:** The dataset was analyzed to see how feedback is distributed across different resource persons, showing a varied participation rate.

- **Participant Name Analysis:** A value counts normalization showed the number of feedback entries per participant, indicating engagement levels across participants.
- **Visualization:** Several visualizations were created to understand the faculty-wise distribution of data, the distribution of ratings across different categories, and the distribution of feedback by branch of study.

## Faculty-wise Distribution of Data:

- The bar graph and pie chart show the count and percentage distribution of sessions handled by different resource persons.
- Mrs. Akshara Sasidharan and Mrs. Veena A Kumar appear to have the highest number of sessions, with Mrs. Gayathri J L and Dr. Anju Pratap having a smaller share.

## Content Quality:

- The boxplot for content quality across different resource persons indicates high median ratings, suggesting overall positive feedback.
-  There are no outliers, and the interquartile range is narrow for all, which means the ratings were consistently high across participants.
