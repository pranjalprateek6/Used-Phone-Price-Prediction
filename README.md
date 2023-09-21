# Used Phones Pricing Analysis and Prediction
<p align="center">
<img src="https://i.imgur.com/M29eSKC.gif" width="500" height="500" />
</p>

## Introduction

Used phones and tablets have become increasingly popular in both the global and Indian markets in recent years. The rise of e-commerce platforms, improved quality of refurbished devices, and the increasing affordability of technology have all contributed to this trend.

Around the world, consumers are realizing the many benefits of purchasing used devices. Not only do these devices offer a more affordable alternative to brand-new gadgets, but they also have a smaller environmental impact. Many consumers are also attracted to the idea of reducing waste by giving new life to a previously-owned device.

In addition to being more affordable, used phones and tablets in India often come with a warranty, providing peace of mind to consumers who may be worried about purchasing a previously-owned device. This, combined with the improved quality of refurbished devices, has made used phones and tablets a popular choice for many consumers in India.

In addition, companies that collect and refurbish used devices can also collect valuable data and insights about consumer behavior and preferences, which can inform their future product development and marketing efforts. Overall, the collection and reselling of used phones and tablets can be a profitable and socially responsible business model for companies.

## Problem Statement

As a data scientist working at a company specializing in the collection and resale of used phones and tablets, the goal is to build a regression model to predict the used price of these devices. This information is crucial for the company to effectively price their devices and maximize their profits.

The dataset contains information about the used phone prices and tablets, including the model, OS, battery, screen size, storage capacity, and other relevant features. The task is to perform exploratory data analysis (EDA) on the dataset to understand the underlying relationships and patterns in the data, and then build a regression model to predict the used price of the devices.

The final model should be highly accurate and able to generalize well to unseen data. This project will provide valuable insights into the used phone and tablet market and enable the company to make informed pricing decisions.

## Ways to approach

• **What is the problem you're trying to solve?** 
    The goal is to build a regression model to predict the used price of these devices.

• **What data do you have available?** Data containing the information about the used phone prices and tablets, including the model, OS, battery, screen size, storage capacity, and other relevant features.

• **What are the potential solution(s) you can implement?** Analyzing the features to find out the pattern and relationhip with the target 
variables that could help in getting better evaluation results

• **What performance metrics will you use to evaluate your solution?** Using MSE and R2 score to evaluate the regression model

• **What techniques will you use?**

        * Data processing
        * EDA
        * Feature Engineering
        * Scaling and Normalization
        * Model Selection and Evaluation
        * Test the model
        
• **How will you validate your solution?** Model which provides low MSE and high R2 score close to 1 would be validation point to select the best model

## Insights

* **Samsung** was the most reused phone next to phone brands which are categorized as **Others**. 
* There are more people using **Android** OS
* Screen size is mostly between **10-15**
* **4g and 5g** users are more
* Rear camera mp range is mostly between **5-15** mega pixels
* Front camera mp range is mostly between **0-10** mega pixels
* Internal memory is mostly between **0-100**
* Phones ram storage is mostly between **3-5** GB
* Battery life is mostly around **3000** mah
* Weight is around **150-210**
* Most of the phones were released between **2013-2015**
* People have used the phones on an average between **600-800** days which is approximately 2-2.5 years
* Average normalized used price was between **4.2-5** k
* Average normalized new price was between **5-6** k
* Most of the features has rising relationship with the target variable --> normalized used price
* **Linear Regression** with top 5 features was considered to be the best model for this problem.

## What I've learnt!

* Plotting histogram using subplots makes visualization easier
* If we need to remove the last plot in a subplot for the visualizations which has odd number(eg: 11 plots but subplots shows 12), we can remove last one using **delaxes**
* Using **regplot** on bivariate analysis helps us to identify the rising/falling relationship with target variables
* **SelectKBest** in feature selection can be used to pick up top K number of features which can used in model training
* PCA can be used for dimensionality reduction

-----------------------------------------------------------------------------------------------------------------------

Dataset: https://www.kaggle.com/datasets/ahsan81/used-handheld-device-data

Kaggle link:
