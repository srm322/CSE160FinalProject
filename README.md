# CSE160FinalProject 

Replication:
To replicate the results, it would be imperative to collect the same type of data which includes number of firearm deaths per county, number of guns owned per county, number of births per county, and average income per county. Split the data into training and test data with 80% of the data going to the training and 20% of the data going to the test. Then using the CaTools, ROCR, and e1071 libraries build a ROC curve that plots logistic regression as well as a naive bayes classifier. Afterwards utilize the rpart, rpart.plot, and caret libraries to build a decision tree model using the same training and test data as before. Lastly, run a 10-fold cross validation Naive Bayes classifier using the e1071 library. Analyze the results of each model and check for overfitting.

NumbGunsPerCounty:

&nbsp;&nbsp;&nbsp;&nbsp; Couldn't find data on Washington D.C, so I'm not gonna include that data for this project... I can add it real quick to other datasets if needed. Recalculated values for combined data since there were more locations covered, like independent cities, covered in the dataset. 

Works Cited

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; https://worldpopulationreview.com/state-rankings/gun-ownership-by-state

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; https://www.alphalists.com/geo/states

# 

FirearmFatalities:

&nbsp;&nbsp;&nbsp;&nbsp; Note: Blank values reflect unreliable or missing data

Works Cited:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; https://www.countyhealthrankings.org/explore-health-rankings/measures-data-sources/county-health-rankings-model/health-factors/social-and-economic-factors/community-safety/firearm-fatalities

# 

ViolentCrimePerCounty:

&nbsp;&nbsp;&nbsp;&nbsp; Data came straight from website, so I may need to rearrange the data. Cleared data not relevent to 2019 and cleard rows with total state data. 

Works Cited: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/totals/

PersIncomePerCounty:

&nbsp;&nbsp;&nbsp;&nbsp; County names include state as 2 letter abbrieviation at end, which may cause problems. 

Works Cited:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; https://www.bea.gov/news/2021/personal-income-county-and-metropolitan-area-2020


CombinedData:

&nbsp;&nbsp;&nbsp;&nbsp; When combining ViolentCrimePerCounty and PersIncomePerCounty, there were fewer counties covered in PersIncomePerCounty that was not in ViolentCrimePerCounty. I marked these with NA. There is no Data for Washington DC in FirearmFatalities and NumbGunsPerCounty, so may delete (depends on group decision). 
