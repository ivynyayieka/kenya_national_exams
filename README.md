# Hypothesis tests for the impact of election years on Kenya's national examination results 

##### Is there a difference between the top scores of candidates in Kenya's national examinations on years when there is an election compared to years where there is none?

KCPE: Kenya Certificate of Primary Education, a national exam taken by students in grade 8 across the country, usually about 12 to 14 years old. <br/>
KCPE: Kenya Certificate of Secondary Education, a national exam taken by students in Form 4 across the country, usually about 16 to 18 years old.


#### Null hypothesis:
There is no difference between the top scores of candidates in Kenya's national examinations on years when there is an election compared to years where there is none.

👉 Summary

In this project, I plot the percent of candidates that got high scores in their KCPE and KCSE exams. <br/>
Through the t-tests, I test whether the difference between the scores in the election years and those in the non-election years is significant in the KCSE exams.


👉 Reflection

What I can conclude based on this analysis:
* This project is helpful for seeing the percent of candidates that got the highest scores in their exams by year.
* It appears that it is possible that the election years are not very influential on the  scores in the top band.
* The p-value in all the cases tested is higher than 0.1 at about 0.7, indicating there is no statistically significant difference between examination results in election years compared to other years. This is a conclusion that can be supported by the initial plotting of the data which showed the data may be randomly distributed.
* Some of the plotting however reveals that the percentage of candidates making the highest scores are roughly distributed in two different clusters, meaning something other than the election years could be significantly affecting the percentage of top scorers. (Note: In preliminary analysis in the scratchpad, it appeared cabinet secretaries were more influential in the kinds of results candidates got than election years)


What I can't conclude based on this chart: 
* Since it is possible other variables are affecting the distribution, I do not know yet which exact variable could be affecting the top scores.
* I cannot make a global conclusion about a lack of correlation between election years and exam results because the plotting reveals only about 25% of the data is from election years. Perhaps more data would more reliably help make one conclusion or other

#### I have failed to reject the null hypothesis that there is no difference between the top scores of candidates in Kenya's national examinations on years when there is an election compared to years where there is none.

#### Reader-facing conclusion:
Whether or not it is an election year does not affect the grades of candidates scoring the highest marks in Kenya's national examinations. Top candidates taking their national examinations in Kenya on election years are not likely to get higher or lower scores than candidates taking their exams on years when there are no elections.

#### Data sources:
See [data_sources.md](https://github.com/ivynyayieka/kenya_national_exams/blob/main/data_sources.md) in repo
