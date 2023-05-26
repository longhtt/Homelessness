# DATA 3320 (project 3: Homelessness)

## Description 
using the data science methodology to investigate homelessness in the U.S., predict homelessness rates based on local housing market factors.

## conclusion
the overall aim of this analysis was to see how well or in correct term, how accurate can we predict homeless rate. Overall with changing the data to only include 2017 data and no other years. This makes our data very small to make an accurate prediction with. At most with using lasso, ridge regression and XGBoot, we would only get around 10%-15% accuracy in predicting homelss rates. This just goes to show how important it is to have a large data to help with prediction. if this was simply to show data, it would be fine, but prediction require much more.

## Requirements
no requirements

## Data 
The data for this project are described in HUD’s report [Market Predictors of Homelessness](https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf) to an external site. in the section titled DATA.

## Data Preparation
before an analysis can be made, the data given has many predictors we can use but many of them do not much impact in helping predict the rate of homelessness. Following the Colab notebook [DATA_3320_Homelessness_Data_Preparation_Long_Tran-Thien.ipynb](https://github.com/longhtt/Homelessness/blob/main/DATA_3320_Homelessness_Data_Preparation_Long_Tran-Thien.ipynb) we can see how the clean data [clean_homeless_data.csv](https://github.com/longhtt/Homelessness/blob/main/clean_homeless_data.csv) was created

### short summery of steps taken to prep clean_homeless_data.csv
1. Import libraries
2. Load the data
3. Explore the contents of the data set
4. Explore the data sources
5. Select relevant subsets of the data
6. Checking the data if suitable for answering the question?
7. Rename columns
8. Quality Control
9. Identify and deal with missing values
10. Create relevant derived variables as new columns
11. Export the clean .csv files

## Data Anaylsis
using the clean data file created from the data preperation, created a analysis notbook [DATA_3320_Homelessness_Analysis_Long_Tran_Thien.ipynb](https://github.com/longhtt/Homelessness/blob/main/DATA_3320_Homelessness_Analysis_Long_Tran_Thien.ipynb)

### short summery of steps taken to prep DATA_3320_Homelessness_Analysis_Long_Tran_Thien.ipynb
1. Introduction
2. Import libraries
3. Load clean data
4. State questions
5. Analysis
6. Lasso
7. Ridge 
8. XGBoost
9. addition step
10. conclusion

## Authors
Creator of repository: Long Tran-Thien

## License
Anyone may reuse material from this repository but must credit me 'Long Tran-Thien'
