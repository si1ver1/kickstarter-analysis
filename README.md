
# Kickstarting with Excel

## Overview of Project

### Visualize Theatre campaign outcomes on Kickstarter based on their launch dates and their funding goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Outcomes_vs_Goals](https://raw.githubusercontent.com/si1ver1/kickstarter-analysis/master/resources/Theater_Outcomes_vs_Launch.png)
According to the Theatre Outcomes vs Launch chart we can see that both successful and failed campaigns share a similar trend with successful campaigns taking the lead. There are a larger number of successful campaigns in May and towards the end of the year in December this dips down to almost even with the failed campaigns. Canceled campaigns stay relatively even throughout most of the months.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://raw.githubusercontent.com/si1ver1/kickstarter-analysis/master/resources/Outcomes_vs_Goals.png)
Viewing the Outcomes Based on Goals chart we see a negative correlation where the success rate of a campaign decreases as the goal amount increases with a break between the $35,000 to $45,000 goal range where campaigns are more successful again.

### Challenges and Difficulties Encountered
Some issues that posed a challenge were using the COUNTIFS statement in Excel to count the outcomes based on goals. Initially a missing " caused a failure in the equation.

## Results

##### Based on the launch date, theatre campaigns are more likely to be successful
- in the first 6 months of the year vs the last 6 months
- are most successful in May

##### According to the outcomes based on Goals
- Campaigns with cheaper goals are more likely to success


##### Limitations with this dataset
Through this data set we are unable to see why the negative correlation breaks when the goal range reaches $35,000. Most likely there is some other external factor in play here. We also don't factor in the spotlight and staff pick columns. We could graph those against the outcome to see if there is any campaigns with those factors are more likely to succeed