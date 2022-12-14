# Richter's Predictor: Modeling Earthquake Damage

ReadMe

This started as a logistic regression / decision trees exercise.
After working on this notebook I started working on the ( Richter's Predictor competition) hosted by DrivenData.
Spoiler: I am still at rank 400 as of 2022 - 12 -14.

sub_7468_2022-12-14.csv 
- rank 400 on driven data as of 2022 12 14
- scored 0.7447 
- no oversampling
- not including 'geo_level_1_id'

sub_7123_2022-12-14.csv 
- catboost validation score  0.7123
- with oversampling
- not including 'geo_level_1_id' 


sub_71015_2022-12-14.csv
- with oversampling
- including all cat features
- new column for 'age above 220' and 'age below 100'
- added eval metric = 'TotalF1'


sub_74794_2022-12-14.csv 
- catboost validation score  0.74795
- no oversampling
- including all cat features
- new column for 'age above 220' and 'age below 100'
- added eval metric = 'TotalF1'
- up to 300 iterations


sub_74644_2022-12-14.csv 
- catboost validation score  0.74644
- no oversampling
- including all cat features
- new column for 'age above 220' and 'age below 100'
- new column for 'height' and 'area'
- added eval metric = 'TotalF1'
- up to 300 iterations



sub_74816_2022-12-14.csv 
- Shrink model to first 496 iterations.
- catboost validation score  0.74817
- no oversampling
- including all cat features
- new column for 'age above 220' and 'age below 100'
- new column for 'height' and 'area'
- added eval metric = 'TotalF1'
