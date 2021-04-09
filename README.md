# DATA115_Personal_Dataset

## Motivation

Currently, I work as a bookkeeper for a non-profit that helps women find alternatives to abortion. Although abortion can be a choice, sometimes women are pressured into that decision by their financiances, family, partner, etc. Abortions can have long-term consequences, not only physical but also emotional. Because of its relation to my job and the gravity of abortions, I decided to use abortion statistics for my dataset. 

Initially, the question for my analysis was going to be "Which state has the highest number of abortions between 2009 and 2018?" Upon further analysis, I realized there are at least two methods according to the CDC to determine the number of abortions per state. You could use the number of abortions by maternal residence or the state that the service was performed in. For purposes of this analysis, I am going to use the number of abortions by the state the service was performed in. Therefore, I modified my question to be "Which state has performed the highest number of abortions between 2009 and 2018?"

## Data Process

My datasource for this project is the Center for Disease Control and Prevention (CDC). The CDC collected Abortion surveilance reports from different states and reporting areas. On their website, they provide a xls file of abortions across states for the period 2009-2018 for personal analysis. Using this file as a basis, I spliced the columns "total by location of service" for each year to the state name column in a new workbook. States that did not provide reportable data or did not report at all for any of the years were excluded from the analysis. The states California, Maryland, New Hampshire and Wyoming did not report for any of the years under analysis while Delware and the District of Columbia did not report for 2009 and 2016 respectively. Although Florida only reported by occurrence, it was allowed to remain in the analysis because it had data for all the years in question. In addition, I added a totals column adding up all of the yearly totals for each state. I also combined New York City and New York rows to get the total abortions performed in that state. 

## Visualization

https://raw.githubusercontent.com/katiekealy/DATA115_Personal_Dataset/main/R_pic.png
caption: States that performed over 500,000 abortions between 2009 and 2018. 
