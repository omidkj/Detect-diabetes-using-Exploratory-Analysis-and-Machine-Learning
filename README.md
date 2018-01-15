# Detect-diabetes-using-Exploratory-Analysis-and-Machine-Learning
This project conducts exploratory analysis and utilizes sci-kit learn to train and test a support vector machine (SVM) to detect diabetes using the diabetes data set from the UC Irvine machine learning repository:
* Obtain aggregate statistics on each predictor variable and preprocess data appropriately. Create plots to tell the story of the data: display the distribution of each variable and relationships between some of the variables.
* Partition the dataset into training and testing sets.
* Using 2 different kernels (rbf and polynomial), train support vector machines to classify examples into control (0) and case (1). Select the best model for each kernel. Also record prediction accuracy, confusion matrix and area under the ROC curve.



Information about the data set:

Abstract: From National Institute of Diabetes and Digestive and Kidney Diseases; Includes cost data (donated by Peter Turney)
Data Set Characteristics:
 
 * Data Set Characteristics: Multivariate
 * Number of Instances: 768
 * Area: Life
 * Attribute Characteristics: Integer, Real
 * Number of Attributes: 8
 * Date Donated: 1990-05- 09
 * Associated Tasks: Classification
 * Missing Values? Yes
 * Number of Web Hits: 125423
 
     
 Attribute Information:
1. Number of times pregnant
2. Plasma glucose concentration a 2 hours in an oral glucose tolerance test 3. Diastolic blood pressure (mm Hg)
4. Triceps skin fold thickness (mm)
5. 2-Hour serum insulin (mu U/ml)
6. Body mass index (weight in kg/(height in m)^2)
7. Diabetes pedigree function
8. Age (years)
9. Class variable (0 or 1)

** UPDATE: Until 02/28/2011 this web page indicated that there were no missing values in the dataset. As pointed out by a repository user, this cannot be true: there are zeros in places where they are biologically impossible, such as the blood pressure attribute. It seems very likely that zero values encode missing data. However, since the dataset donors made no such statement we encourage you to use your best judgement and state your assumptions.
