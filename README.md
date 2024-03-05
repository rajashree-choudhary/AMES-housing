# Kaggle Challenge For Ames Housing Data

## Summary

### Problem Statement

In this challenge, you will use the well known Ames housing data to create a regression model that predicts the price of houses in Ames.

### Goal

The goal of this project is to predict the sales price for each house and also find what are the feautures of the house matters which buying or selling the house.

#### Table of Contents:
- Discussion and Background Cleaning
- Visualizing data Featuring matrix 
- Model Fitting Model Evaluation Prediction that model with given testing data Findings
- Recommendation of the project

#### Original Dataset
- train.csv
- test.csv

#### Sample Dataset Dictionary

- SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict for this challenge.
- MSSubClass: The building class
- 20 1-STORY 1946 & NEWER ALL STYLES
- 30 1-STORY 1945 & OLDER
- 40 1-STORY W/FINISHED ATTIC ALL AGES
- 45 1-1/2 STORY - UNFINISHED ALL AGES
- 50 1-1/2 STORY FINISHED ALL AGES
- 60 2-STORY 1946 & NEWER
- 70 2-STORY 1945 & OLDER
- 75 2-1/2 STORY ALL AGES
- 80 SPLIT OR MULTI-LEVEL
- 85 SPLIT FOYER
- 90 DUPLEX - ALL STYLES AND AGES
- 120 1-STORY PUD (Planned Unit Development) - 1946 & NEWER
- 150 1-1/2 STORY PUD - ALL AGES
- 160 2-STORY PUD - 1946 & NEWER
- 180 PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
- 190 2 FAMILY CONVERSION - ALL STYLES AND AGES
- MSZoning: Identifies the general zoning classification of the sale.
- A Agriculture
- C Commercial
- FV Floating Village Residential I * Industrial
- RH Residential High Density
- RL Residential Low Density
- RP Residential Low Density Park
- RM Residential Medium Density
- LotFrontage: Linear feet of street connected to property
- LotArea: Lot size in square feet
- Street: Type of road access to property
- Grvl Gravel
- Pave Paved
- Alley: Type of alley access to property
- Grvl Gravel
- Pave Paved
- NA No alley access
- LotShape: General shape of property
- Reg Regular
- IR1 Slightly irregular
- IR2 Moderately Irregular
- IR3 Irregular
- LandContour: Flatness of the property
- Lvl Near Flat/Level
- Bnk Banked - Quick and significant rise from street grade to building
- HLS Hillside - Significant slope from side to side

[Click Here to Read more about Data Dictionary](https://www.kaggle.com/competitions/dsi-122-ames-housing-challenge/data) 


### Recommendation:

We find that there are quite a few features that seem to show strong correlation to SalePrice, 
such as Overall Quality,Total Square-feet, Total basement Square feet, Ground Living area, and Totall rooms above the ground. This confirms our natural intuition: we would expect that high quality, big house with big basements and lots of rooms to be more expensive.
