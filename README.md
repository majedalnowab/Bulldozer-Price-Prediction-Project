# Bulldozer-Price-Prediction-Project
## Description
![image](https://github.com/user-attachments/assets/3771edc8-c452-4316-89ea-19ff2840e732)

The goal of the contest is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration.  The data is sourced from auction result postings and includes information on usage and equipment configurations.

Fast Iron is creating a "blue book for bull dozers," for customers to value what their heavy equipment fleet is worth at auction.

## About Fast Iron
Fast Iron are a content-focused business that aids customers in creating enterprise data standards, cleansing data, and maintaining clean data. Utilizing proprietary applications and an ever growing data cleansing team, Fast Iron has normalized data for more than 2.5 million machine and customer records for the heavy equipment industry.

This competition was launched under the Kaggle Startup Program. If you're a startup with a predictive modelling challenge, please apply!

## Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

Sample submission files can be downloaded from the data page. Submission files should be formatted as follows:

Have a header: "SalesID,SalePrice"
Contain two columns
SalesID: SalesID for the validation set in sorted order
SalePrice: Your predicted price of the sale
Example lines of the submission format:
SalesID,SalePrice
1222837,36205
3044012,74570
1222841,31910.50
...


## Timeline
Friday, January 25, 2013: Competition launch: training set and validation sets released

Wednesday, April 3, 2013: Deadline to submit predictions on the validation set, public leaderboard frozen.

Thursday, April 4, 2013: Validation set solutions released. You may retrain your models on the combined training and validation sets at this point.

Wednesday, April 10, 2013: Deadline to upload final models. You only need to upload a model to be eligible for prize money (we recommend this if you are in the top 20 or think you have a shot for the prize money).

Thursday, April 11, 2013: Test set released. You now have one week to make predictions on this set and submit your predictions to Kaggle. You don't need to have uploaded a model to make your test set predictions and appear on the final leaderboard.

Wednesday, April 17, 2013: Deadline for submitting test set predictions.


## Citation
Ben Hamner, Fast Iron 2, and FastIron. Blue Book for Bulldozers. https://kaggle.com/competitions/bluebook-for-bulldozers, 2013. Kaggle.
