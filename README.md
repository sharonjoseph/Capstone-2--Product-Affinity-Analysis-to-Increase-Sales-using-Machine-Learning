# Capstone-2--Product-Affinity-Analysis-to-Increase-Sales-using-Machine-Learning

The objective of this study is to leverage customer firmographic data and product sales transaction data to build a solution to project the likelihood of a purchase from our existing customer base.

The data required for this study is drawn from the organization’s internal Salesforce system. The customer and product transaction data thus obtained is cleaned, processed and merged into a single dataset for building the analytical models. The data is in masked format to protect the organizations data privacy.

Machine learning algorithms like Market Basket Analysis using Apriori, Total Unduplicated Reach and Frequency Analysis (TURF) for frequency study, Chi-square Automatic Interaction Detector (CHAID) algorithm for the Decision tree, K-Nearest Neighbour (KNN) and Multilayer Perceptron (MLP) as part of Deep Learning are the techniques used to derive the desired outcome to the problem. 

Data files is a zipped folder containing the data files 
a. MaskedTruthTable.csv - csv file with truth table
b. FinalModelData.xlsx - excel file with the target variables created along with the dependent variables 

MBA Results - excel file with the results from running the apriori algorthim. The second sheet in same file ahs the web chart.

TURF.htm - output file for the TURF analysis carried out to analyse the total unduplicated reach and frequesncy of products within our dataset.

MLModelsOutput.htm - output file for the different models that are run for analysis KNN, Decision Tree-CHAID, DeepLearning-MultiLayerPerceptron.

Sharon Stream1.str - this file is the stream created while running Apriori algorithm after splitting data to test and train (70-30 ratio).

** This project has data acquired from the company. Hence there are data privacy concerns and limitations to share further data.
