# Project 1: SAT & ACT Analysis

## Problem Statement

This project aims to help executives with the College Board improve SAT participation rates by providing recommendations on where money is best spent to achieve that goal.

## Executive Summary
### Methodology:
The project will examine trends in SAT and ACT participation rates during 2017 to 2018, in order to identify states the College Board might target to increase SAT participation.
Additional research will be conducted on state policies that might influence these rates.

### Contents:
- [01. 2017 Data Import and Cleaning](https://github.com/kevinacrystal/SAT_ACT_Analysis/blob/master/code/2017%20Data%20Import%20and%20Cleaning.ipynb)
- [02. 2018 Data Import and Cleaning](https://github.com/kevinacrystal/SAT_ACT_Analysis/blob/master/code/2018%20Data%20Import%20and%20Cleaning.ipynb)
- [03. Exploratory Data Analysis](https://github.com/kevinacrystal/SAT_ACT_Analysis/blob/master/code/Exploratory%20Data%20Analysis.ipynb)
- [04. Data Visualization](https://github.com/kevinacrystal/SAT_ACT_Analysis/blob/master/code/Data%20Visualization.ipynb)
- [05. Outside Research](https://github.com/kevinacrystal/SAT_ACT_Analysis/blob/master/code/Outside%20Research%2C%20Conclusion%2C%20Recommendations.ipynb)
- [06. Conclusions and Recommendations](https://github.com/kevinacrystal/SAT_ACT_Analysis/blob/master/code/Outside%20Research%2C%20Conclusion%2C%20Recommendations.ipynb)

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|object|ACT|The US state to which the data applies| 
|**2017_act_participation**|int|ACT|The percentage of students in the state who took the ACT in 2017| 
|**2017_act_english**|float|ACT|The average 2017 ACT English score for the state (scored between 1 and 36)| 
|**2017_act_math**|float|ACT|The average 2017 ACT Math score for the state (scored between 1 and 36)| 
|**2017_act_reading**|float|ACT|The average 2017 ACT Reading score for the state (scored between 1 and 36)| 
|**2017_act_science**|float|ACT|The average 2017 ACT Science score for the state (scored between 1 and 36)|
|**2017_act_composite**|float|ACT|The average 2017 ACT Composite score for the state; the Composite score is the average of the four subject scores (enlish, math, reading, science)| 
|**2017_sat_participation**|int|SAT|The percentage of students in the state who took the SAT in 2017| 
|**2017_sat_evidence-based_reading_and_writing**|int|SAT|The 2017 average SAT Evidence-Based Reading and Writing score for the state (scored between 200 and 800)| 
|**2017_sat_math**|int|SAT|The 2017 average SAT Math score fore the state (scored between 200 and 800)| 
|**2017_sat_total**|int|SAT|The 2017 average total score for the state; total score is the sum of evidence-based_reading_and_writing and math, so it can range from 400 to 1600|
|**2018_act_participation**|int|ACT|The percentage of students in the state who took the ACT in 2018|
|**2018_act_composite**|float|ACT|The 2018 average ACT Composite score for the state|
|**2018_sat_participation**|int|SAT|The percentage of students in the state who took the SAT in 2018|
|**2018_sat_evidence-based_reading_and_writing**|int|SAT|The 2018 average SAT Evidence-Based Reading and Writing score for the state|
|**2018_sat_math**|int|SAT|The 2018 average SAT Math score for the state|
|**2018_sat_total**|int|SAT|The 2018 average SAT Total score for the state|

## Conclusions and Recommendations
Based on exploration of the data and outside research, the largest increases in SAT participation rates are due to the exam being mandated by the state; the College Board should focus on getting states to add the SAT as a graduation requirement for high school students.

Oregon had 2018 participation rates below 50% for both the SAT and the ACT, and could be a good state to target for state-mandated testing.

## Sources
https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/  
https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows  
https://reports.collegeboard.org/sat-suite-program-results/state-results  
http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf  
http://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html  
https://www.cde.state.co.us/assessment/coloradosat  
https://www.usnews.com/news/best-states/rhode-island/articles/2018-10-25/sat-participation-increases-scores-decline-in-ri

