# Lending_Club_Analysis_and_Modeling: Predicting bad loans from Lending Club data
 
The purpose of this project is to understand what makes a user default a loan from LendingClub.  

Each line item in the data corresponded to a loan, and had various features relating to loan amount, employment information of the borrower, payments made and so on. I will layout the most influencing parameters by considering both the statistical and lexicon based NLP modeling for the prediction.

Apart from that, an exploratory data analysis was performed on the data, to look for outliers and individual distributions of the variables. Following which, the interactions between these variables were studied to weed out highly correlated variables. There are very few representation of defaults in the data compared to the fully paid class. Therefore, this was treated as an imbalanced class problem, wherein traditional random sampling would not yield optimal results. 

To overcome this problem, I performed SMOTE for data class balance. To best classify which loans would likely default from the given dataset, various statistical learning techniques, such as Regression, Tree-based methods- standalone, boosting and bagging ensemble methods, Support Vector Machines and Neural Networks were employed. Amongst these classifiers, Gradient boosting was observed to have the best performance, although with further fine tuning, Deep Neural Networks could possibly classify better.
