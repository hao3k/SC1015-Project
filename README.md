# Welcome to SC1015 C133_Team 5 Mobile Phone Repository

## About

This is our Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on [mobiles.csv](https://github.com/hao3k/SC1015-Project/blob/2c4896a008a06358d48cdc41d9f78460acb7d6a8/mobiles.csv) dataset from [Kaggle](https://www.kaggle.com/datasets/anas123siddiqui/mobiles). Detailed analysis are inside the notebook file under the markdown section. For detailed walkthrough, please view the source code in order from:

1. [Data Preprocessing, Cleaning and Exploratory Analysis](https://github.com/hao3k/SC1015-Project/blob/03f3bb1b06dbaa1e1276358b4498a3e190974c7d/Data%20Preprocessing,%20Cleaning%20and%20Exploratory%20Analysis.ipynb)
2. [Model 1 K Nearest Neighbours](https://github.com/hao3k/SC1015-Project/blob/03f3bb1b06dbaa1e1276358b4498a3e190974c7d/Model%201%20K%20Nearest%20Neighbours.ipynb)
3. [Model 2 Linear and Polynomial Regression](https://github.com/hao3k/SC1015-Project/blob/f4de5b1644de44fcb8d114681766687f68e765d9/Model%202%20Linear%20and%20Polynomial%20Regression.ipynb)
4. [Model 3 Random Forest](https://github.com/hao3k/SC1015-Project/blob/4cefb07b7b3c50c0077d0c665f70a75902f69b6f/Model%203%20Random%20Forest.ipynb)

## Members
- @hao3k - Hang Hao Kuang
- @Cheechengm - Mak Chee Cheng
- @Vignesh-Tharun - Vignesh Tharun

## Introduction & Problem Statement

The rise of smartphones has revolutionized the way we communicate and interact with the world around us. With numerous mobile phones of different brands and specifications available, it can be challenging to determine which phone is the most suitable for a user's needs. Therefore, the aim of our project is to predict mobile phone user ratings based on various variables.

Project Objectives:
The main objective of this project is to predict how good a mobile phone is based on its variables and ratings. This prediction will assist in several ways, including:

1. Helping the brand improve based on which specifications the user feels are better: By analyzing the user ratings, we can identify which phone features the user values the most and which ones need improvement. This information will be beneficial for phone manufacturers as they can improve the phone's features according to the users' needs.
2. Help the brand predict how well their new phone will fair in the market based on its specifications.
3. Identifying the deciding factors that users look out for in a good phone: Through this project, we aim to identify the critical factors that contribute to a good phone rating. This knowledge will be useful for phone manufacturers to design phones that cater to the users' requirements.

4. Assisting users in sourcing for the phone that suits them best: By predicting the mobile phone user ratings, we can help users source for the phone that suits their needs. Users can search for a phone based on their requirements, and the model with the highest predicted rating will be the most suitable for them.

This project aims to predict mobile phone user ratings based on various variables to assist both phone manufacturers and users. It will provide valuable insights into which phone features the user values the most, the critical factors that contribute to a good phone rating, and assist users in sourcing for the phone that suits them best.

## Model Used
1. Model 1: K Nearest Neightbours Model, GridSearchCV model, Bagging Model
2. Model 2: Linear and Polynomial Regression Model
3. Model 3: Random Forest Model


## Conclusion
Upon comparing the three major models of k Nearest Neighbours, Linear/Polynomial Regression and random forest, our attempts indicates that K Nearest neighbours is the most accurate model with the lowest Mean Squared Error (MSE) of 0.0283 & the highest score of 0.4285. Therefore, K Nearest Neighbours is chosen as our final model for our problem statement.

We have four main interesting observations.
1. We realised that, despite using a more complex model such as bagging on top of k nearest neighbours, the accuracy did not increase, thus proving that a more complex model does not neccesarily improve the accuracy of the model.
2. Adding more predictors does not always improve the model but, in turn, causes overfitting and reduces accuracy.
3. Larger screen size seems to be the most prominent specification in deciding the phone's star rating.
4. Due to the nature of our star rating being from 3.3 to 4.7 and a single decimal place, It can be predicted as a numerical or categorical variable, which opens up more possibilities for more models.
 
--------------------------------------------------------------------------------------------------------------
From our analysis, we have two major insights.
1. A bigger screen size and battery is positively correlated with a higher star rating. This might be because a bigger screen enables the user to have more things displayed at the same time, and the battery allow loger usage which helps to improve the user's productivity, thus placing it at a higher demand and rating.
2. Higher sale price seems to result in a better rating, which might be due to the user perceiving a higher sale price as a margin for better quality, thus causing people to pursue a higher priced phone.
 
 
--------------------------------------------------------------------------------------------------------------
Next are our recommendations for our project and problem.
1. We recommend that the phone company continue to upgrade their screen and battery qualities to have a higher rating and to stay relevant in the phone market.
2. Even with numerous attempts to improve accuracy, our best score is only 0.4285. which is relatively low. Thus, maybe trying a different model than those attempted might yield a better outcome.
3. The lack of data in the dataset with all the NA in different predictors and NA being the majority for some predictors resulted in lower accuracy. Thus, trying a different mobile phone dataset with fewer missing data points might improve our model.
 

In conclusion, our model is relatively accurate in predicting the Stars rating of mobile phones, and this can provide insights to companies to identify the phone specifications that impact ratings, thereby improving sales and earnings. For potential phone buyers, our model can offer useful information on phone performance based on specific features and user requirements. Therefore, we believe that our predictions using the mobile phone dataset are valuable in the world of emerging technologies.

## Task Allocation
1. Cleaning & preprocessing - All Members
2. Exploratory analysis - All Members
3. Model 1 - Hang Hao Kuang
4. Model 2 - Mak Chee Cheng
5. Model 3 - Vignesh Tharun
6. Slides and Voice Recording - Hang Hao Kuang & Mak Chee Cheng
7. Video Compilation, Enhancement & Subtitles - Vignesh Tharun

## References
- https://towardsdatascience.com/understanding-random-forest-58381e0602d2
- https://realpython.com/knn-python/ 
- https://www.kaggle.com/datasets/anas123siddiqui/mobiles
- https://medium.datadriveninvestor.com/random-forest-pros-and-cons-c1c42fb64f04
- https://www.mygreatlearning.com/blog/knn-algorithm-introduction/

## Miscellaneous/MISC folder
- [Unofficial Report](https://github.com/hao3k/SC1015-Project/blob/9d85d133fee36e1ad5638defa614b2b723b2bea0/MISC/Sc1015%20C133%20Group%205%20Unofficial%20Report.pdf) - Compilation of the things covered in jupyter notebook without the source code
- [Model 2 Datasheet](https://github.com/hao3k/SC1015-Project/blob/9d85d133fee36e1ad5638defa614b2b723b2bea0/MISC/Model%202%20Datasheet.pdf) - Compilation of Model 2 attempts MSE and Score

## License
Copyright (c) 2023 Hang Hao Kuang, Mak Chee Cheng, Vignesh Tharun

Unless otherwise specified, this project (all of the files in this repository) 
is licensed under the MIT License.

For licensing information, see LICENSE.
