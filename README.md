# Sentencing Notes
## Goal
To determine whether Black defendants are more likely to be sent to jail or not.

## Subset of the Data
Taking a slice of five years using arrest date. From January 2019 to December 2019.
This is in part an attempt to not have to deal with the possible effects of Covid.

### Further Subsetting
* Only using Aggravated DUI as the updated offence category
* between 2010 and 2020


## Classification Techniques
The different classification methods I want to try
* Logistic Regression
* Support Vector Machine
* Random Forest/Gradient Boosting Tree

## Visualizations
* Differences between men and women in sentencing


## Possible Feature Engineering
* Create male/female judges
	* Match between male and female judges

## Variables to Keep
* Age
* Race
* Gender
* Incident city
*
## Values to use
* race
* gender
* incident city
* drop NAN
* instead of using updated offence, just use felonies



filtering order
* import full dataset
* update time column to actual datetime
* filter data for the past five years
* drop duplicates for case id
* filter dataset for only felony crimes
* update type for commentment term to float
* filter commitment unit for only day, month, and year values


age between 18 and 39

don't include - incident in chicago or not - not really sure what the
theoretical reason would be anyway 




































1
