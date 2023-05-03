### Name :Lavanya.P
### Batch :2022-8410
### Enrollment No: EBEON112686215
# Holiday-Package-Prediction
A model for predict users who have the potential to buy Wellness Tourism Package.
# Dataset Description
This data is offer data on holiday packages originating from a travel company and plans to expand its business through the latest package offerings, namely the Wellness Tourism Package with the target of whether the holiday package is taken or not(ProdTaken).
# Background and Objective
## The problem behind this analysis.
The company Trips&Travel.com wants to launch a new vacation package called the Wellness Tourism Package. Unfortunately, they have a problem with promotion. They contact random customers to offer vacation packages so it is not efficient. Based on last year’s data, Trips&Travel.com has 4888 customers. However, only 18% of the total customers purchased vacation packages.
## The importance of this analysis carried out.
This analysis is important in order that the promotion can run efficiently to optimize the use of costs, with the following objectives that can be broken down into 4:

1.Compare the performance of each algorithm as follows:

Logistic Regression, Decision Tree, Random Forest, SVM,Navie Bayes.

2.Decide which algorithm we will use based on the best performance on the chosen metrics.

3.Percentage of users who bought vacation packages and calculation of Customer Acquisition Cost (CAC).

4.Analyze what kind of customers are more likely to take vacation packages.‍
# Scope of problem
The scope of the problem is to be solved by measuring the following business metrics:

1.Percentage of users who bought vacation packages.

2.Revenue The output of machine learning to be created is to predict users who have the potential to buy vacation package.
# Data and Assumptions‍
This dataset contains 4K (4888) rows and 20 columns. Amongst the columns, we have the target variable is named ‘ProdTaken’, which contains ‘Do the customers take a vacation package?’ (0: No, 1: Yes). This dataset is a mix of numerical and categorical variables. The target variable is in categorical data type and it’s already converted to boolean type. All features are used in machine learning except for the customer ID because previously we have tried to use features consisting of passport, age, monthly income, type of contact, own car, city tier, occupation, marital status, number of follow-ups, number of trips and product pitched. We decided to use those features based on the results of the bivariate and multivariate analyses that we have done before, but when we try to add all the features we get better performance of results.
#Model Analysis
From a total of 246 customers who took vacation packages, as many as 199 could be predicted correctly. we have reached the expected performance 88%.
# Evaluation
Based on the recall score, Random forestclassifier has the best performance compared to other algorithms. The results from the test train are slightly higher than the test results but are still in the range of ~0.85–0.90.
Performance results based on the precision score on Random forestclassifier are also at >=0.50 according to the threshold that we have set, namely with a score of 0.93.
When viewed from the accuracy of the Random forestclassifier modeling, the score is still quite high, namely 0.88
# Conclusion
The final model we chose was Random forestclassifier with 93% performance from the recall matrix or it can be said that this model can predict the number of customers who buy vacation packages by 88%. . Important features to consider in bidding to customers from modeling results using XGBoost are Passport, Designation, Product Pitched, Single Marital Status, and City Tier.
# Business Recommendations Suggestion
For high potential customers

Offering vacation packages to domestic & international destinations for customers who have passports. Offering Wellness packages at low prices, such as Basic & Standard to customers who have never purchased a vacation package and for those who have Executive & Manager positions. Intensifying promotions to customers from big & medium cities. Single offering customers, it is advisable to promote holiday packages outside of major holidays.

For low potential customer

Offering Wellness Packages for domestic destinations for customers who do not have a passport. Offers Wellness Packages with a medium to high price range for those who have at least senior manager positions. Customers who are married will get a Wellness Package promotion on major holidays (such as New Year, etc.).
