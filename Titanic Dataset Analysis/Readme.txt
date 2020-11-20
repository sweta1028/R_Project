Analysis: Exploratory Data Analysis, Data Visualization.

Data Source: https://www.kaggle.com/c/titanic/data
The data has been split into two groups:
training set (train.csv)
test set (test.csv)
We combined it for our analysis.

Dataset Description:
survival:Survival (0 = No, 1 = Yes)
pclass:	Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
sex: Sex	
Age: Age in years	
sibsp: # of siblings / spouses aboard the Titanic	
parch: # of parents / children aboard the Titanic	
ticket:	Ticket number	
fare: Passenger fare	
cabin: Cabin number	
embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)
parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children traveled only with a nanny, therefore parch=0 for them.