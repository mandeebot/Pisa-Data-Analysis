# PISA Data Analysis


## Investigation Overview

>The purpose of this Analysis is to explore how factors like students behaivior, gender and interests affects the  student's performance and Problem solving ability
Other questions this analysis will aim to answer is wether there are differences in achievemets based on gender and student's attitude (drive)


## Dataset Overview

> PISA is a worldwide study by OECD in member and non-member nations intended to evaluate educational systems by measuring 15-year-old students scholastic performance on mathematics, science, and reading.

>The original data set contains 485,490 students and 636 features. Due the extremely large size of our features and the fact that we wanted to focus on gender, we have downsized our data set to include only 10 features.


>My Data cleaning process can be found [here](https://github.com/mandeebot/new_new/blob/main/pisa-data-cleaning-note.ipynb).

>This dataset contains information from 485,490 students and 646 features.
Due low computing resources and the size of the dataset,moving further i will further categorize and streamline the dataset into these categorise for easy analysis.
These will be the features that will be used for my analysis, as i believe they will help me in answering the questions raised.


>Student Information
- CNT: Country
- ST04Q01: Gender

>Motivation
- ST29Q02: Worthwhile for Work
- ST29Q05: Worthwhile for Career Chances
- ST29Q07: Important for Future Study
- ST29Q08: Helps to Get a Job

>Interest
- ST29Q01: Enjoy Reading
- ST29Q03: Look Forward to Lessons
- ST29Q04: Enjoy Maths
- ST29Q06: Interested in Maths

>Behaviour
- ST49Q03: (Extracurricular) Activity
- ST49Q04: Participate in Competitions
- ST49Q05: Study More Than 2 Extra Hours a Day
- ST49Q06: Play Chess
- ST49Q07: Computer programming
- ST49Q09: Participate in Math Club

>Performance
- 'ST01Q01': 'internationalGrade'
- 'PV1MATH': 'MathScore',
- 'PV1READ': 'ReadScore',
- 'PV1SCIE': 'ScienceScore'

For the categorise, i further encoded the categorical values in each category(except the performance category), sumed them up ad average out the scores to have one single category score to represent each  category of features, further cutting down the number of features i have to work with.

## Summary of Findings

>In this exploration, I found that the top performing students were majority males, they showed more interest in Maths and Sciences, but female only edge males in reading.

>We can also see a pattern among the student drive towards math in the top performing students. As the top pecentile of students increases, the male students' average scores for motivation, behavior, perception of parent's attitude towards math, interest, was higher than the female students' average scores under these categories.

>A point worth of mention is that given the high scores of males we also noticed females edged out males in terms of problem solving skills, which begs further questions like since males scored higher on the other performance indexes, why is't this translated into their problem solving skills or ability?

>In conclusion, this Analysis requires further investigations, especially on the relationships between the variables
