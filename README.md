# Abstract
The suicide rate for young people aged 10–14 nearly tripled from 2007 to 2017, according to new data from the CDC. Researchers have also found in recent studies that teenagers (aged 13 to 18) and young adults (aged 19 to 32) who spent the most time on Instagram, Facebook, and other social media platforms were shown to have significantly higher rates of reported depression than those who spent the least.

Is this more than correlation? There’s strong support that time spent on social media has causal effects on children’s mental well-being. According to the Child Mind Institute, a non-profit that works to improve the lives of children struggling with mental health and learning disorders: “...Smartphones were introduced in 2007, and by 2015 fully 92 percent of teens and young adults owned a smartphone. The rise in depressive symptoms correlates with smartphone adoption during that period, even when matched year by year...” 

What measurable effects are there on young people’s mental health when they had higher than average frequency of social media use? Are these effects large and statistically solid? How robust are these effects in the face of unobserved confounding? I’ve explored this research question and found that yes, there were measurable and negative implications on young people’s mental well-being when the amount of time spent on social media crossed a critical threshold. The largest effects were measured in children who reported spending 4 or more hours on a normal school day chatting or interacting with friends on social media apps.


# Methodology
I’ve analyzed select questions and responses from an observational data set in the United Kingdom called “[Understanding Society](https://www.understandingsociety.ac.uk/)”. It’s the largest longitudinal study of its kind, surveying nearly 20,000 U.K. households in the latest survey year 2019 and provides important information for researchers and policymakers on the changes and stability of people’s lives in the U.K. These surveys were initiated in 1991 and have been conducted annually since.

There’s a youth self-completed questionnaire sub-section from the main “Understanding Society” data set, for which kids aged 10 to 15 years old from some of the 20,000 households in the study were asked to respond. It included questions on the child’s time spent on social media, computer- and other screen-time (game consoles, computer games, TV), family support, feelings about different areas of life, health behavior like smoking and drinking, aspirations about their future, etc.

The latest available questionnaire responses were released in 2019. This captured responses to almost 200 questions from 1,800 young people in the U.K. I’ve selected the following questions from this 2019 youth data set as the basis of my analysis:

<p align="center">
  <img src="https://github.com/gracehikes/proj_social_media_teen_mental_health/blob/main/images/project%20report%207%20emoticons.png" width=90% height=90%>
</p>

The regression model is shown below. Y denotes the mental well-being response score, α denotes how the expected well-being response score changes when spending either 1-3 hours, or 4+ hours on social media per school day when compared to the control group who engages on social media for less and an hour each school day. I’ve also included the child’s age, child’s gender, and parents’ educational qualifications in the regression model as observed confounding controls.

<p align="center">
  <img src="https://github.com/gracehikes/proj_social_media_teen_mental_health/blob/main/images/project%20report%20regression%20formula.png" width=65% height=65%>
</p>


# Results
The table below summarizes the measured effects of social media daily use on the young people's survey responses. Among the young people who reported spending 1-3 hours on a normal school day chatting with their friends on social media i.e. treatment group A, the effects on how they felt on the 6 indicators were very small (ranging from -0.09 change in score when asked about their friends, to +0.20 for appearance) and generally not statistically significant.

When we reviewed the responses from “power users” of social media i.e. the young people who spent 4 or more hours per normal school day on social media (treatment group B), the estimated effects on well-being scores were all movement toward the more unhappy end of the 1-7 emoticon scale. Three out of the six indicators of mental well-being exhibited statistical significant treatment effects: feelings about school work (+0.37, p=0.02), school they went to (+0.69, p<0.00001), and life as a whole (+0.49, p=0.0004). 

<p align="center">
  <img src="https://github.com/gracehikes/proj_social_media_teen_mental_health/blob/main/images/project%20report%20effect%20results%20table.png" width=75% height=75%>
</p>


# More Details
Full report found [here](/_project-report---youth-and-social-media---grace-yang.pdf).
