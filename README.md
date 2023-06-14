# Past-R-Studio-Projects
Data Analytics I
Date: 3-14-23

Readme File

## Introduction

This readme file provides an overview of the data and objectives of the project. The project focuses on analyzing household-level responses to the American Community Survey for households in Oregon, using a subset of variables from the 2015 1-year survey. The dataset used in this project is sourced from the Public Use Microdata Sample (PUMS) available at http://www2.census.gov/programs-surveys/acs/data/pums/2015/1-Year/.

The provided dataset contains information for households in Oregon that meet the following criteria: at least one person in the household, payment for electricity, and not classified as a group accommodation. It is assumed that this dataset is a random sample representing all such households in Oregon.

## Explanatory Problem

The primary objective of this project is to address the following question: Do people living in apartments pay less for electricity compared to those living in houses? If so, how much of a difference exists?

To answer this question, a two-sample t-test will be performed by comparing the median cost of electricity separately for houses and apartments. The analysis will take into account the number of bedrooms and occupants in these households. For a fair comparison, the analysis will focus on the following subsets: One-family house detached vs. One-family house attached, and 10-19 apartments vs. 50 or more apartments.

## Prediction Problem

In addition to the explanatory analysis, this project aims to create a predictive model that can estimate electricity costs for households in Oregon. The model will utilize various predictor variables such as housing type, number of bedrooms, occupants, units in structures, house heating fuel, and monthly gas cost.

The predictive model will leverage the relationships identified in the explanatory analysis to estimate electricity costs for future households based on the specified predictors.

Please refer to the documentation and code files for detailed implementation and analysis steps.
