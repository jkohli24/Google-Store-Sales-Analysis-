# Google-Store-Sales-Analysis-

The dataset is a real dataset from transaction track on google store, so if we want to solve the intended business questions, we should follow the process and use the tools:

1.Data preprocessing:
-The dataset has so many dimensions, so should do some EDA to understand the data generation process and the true meaning of the data by plots and graphs (ggplot,plotly)
-The original dataset contains a lot NA value and useless data, so we need do the dataset before we start our analysis 

2.General analysis
-Multidimensional analysis
Different dimensions data may have the same impact on sales, so we should explore the data from many dimensions at the same time. For example, if we want to know more about the sales increase, we should care about the city, time, device etc.
-Correlation analysis
Find some connection between different columns and define Multicollinearity  problem.

3.Advanced analysis
-Regression
The main business questions for us is how sales influenced by multiple channels or campaigns, so the regression will be our primary tool:
Non linear transfer
Interaction: to show the synergy between different columns
Dummy variables: to control different channel and device
-Some other tools not included:
Time series, Logical regression, Customer segmentation

Overview
“The 80/20 rule has proven true for many businesses–only a small percentage of customers produce most of the revenue. As such, marketing teams are challenged to make appropriate investments in promotional strategies” (https://www.kaggle.com/c/ga-customer-revenue-prediction/overview). So, for our final project we are getting the data from Kaggle. This data includes the Google Merchandising data from Google Analytics Demo Account, which is open for the public to practice Analytics . This is a huge Panel data hence has 1.8 million records. We will be taking a sample from the data to perform our analysis for the business problems mentioned in the first part of the proposal. There are several fields in our data set to help our analysis.

The Google analytics dataset have detailed records about individual user’s activities in a session including metrics about page interaction, traffic source, transaction outcome, etc. To answer the business question, we need to evaluate the impact of different attributes in the users’ session in order to find out the most relevant metrics. Google analytics dataset offers complete info about user’s activities which enable us to apply various experiments. The scale of the dataset is moderate, it contains 903k entries. There is also identifiers in the dataset that can be used to group records by user or session which makes it possible for us to analyze continuous behavior of customers.




