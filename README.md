# Wildfire-Detection-Machine-Learning-Project
This is my project, which uses a machine learning system to detect wildfires. In an individual project, I had to preprocess data, apply algorithms, and determine which algorithm produced the best outcome.

What is wildfire?

A wildfire is an uncontrolled fire that burns in the wildland vegetation, often in rural areas. Wildfires can burn in forests, grasslands, savannas, and other ecosystems, and have been doing so for hundreds of millions of years. Wildfires are among the most common forms of natural disaster in some regions, including Siberia, California, and Australia. Areas with Mediterranean climates are particularly susceptible.

Proposal

First the creation of the training and testing dataset. After that, scan the data to identify missing or irregular data as well as the distribution of each feature. After screening, data must be cleaned to
create a trainable set. In addition to creating data, we will also create algorithms (SVM, Random forest, decision tree). Once we have the model and the data, we will train the model and evaluate its performance
on the test set using the metrics of recall, precision, and F1-score. 

Data Sources

Geographic and wildfire data from the State of the California- 4,279 fires from July 1, 2008 to December 31, 2020 Weather data from World Weather Online Historical weather records every day in the same range Aggregated to a monthly basis

About the data set

The Dataset contains: 10,988 records 4,297 of which had fires 
Additional features such as : Monthly weather averages, Quarterly weather averages, Quarterly cumulative precipitation, Acres burned, Cause of fire, Geo Location

Implementation plan

First scan the data to identify missing or irregular data as well as the distribution of each feature. 
After screening, data analysis and correlation plotting. 
After that, the creation of the training and testing dataset. 
After screening, data must be cleaned to create a trainable set. In  addition to creating data, we will also create algorithms (SVM, Random forest, decision tree). 
Once we have the model and the data, we will train the model and evaluate its performance on the test set using the metrics of recall, precision, and F1-score

Conclusion

Accuracy Comparison Data Frame -
<img width="362" alt="image" src="https://github.com/user-attachments/assets/8c4d943e-c0fe-47f6-a773-2cc54e4a6f72">

Accuracy Comparison Bar Graph  -
<img width="363" alt="image" src="https://github.com/user-attachments/assets/8947fbf1-759b-4c0c-a9d7-cf84bc974b45">

Decision tree came out on top with 83% percent accuracy score Random forest has average results due to nonlinear correlation present between features. 
Multilayer perceptron and SVM both gave average results due to overfitting caused by high number of features present in the dataset.

References
 • "California Department of Forestry and Fire Protection", [online] Available: https://www.fire.ca.gov/stats-events/. 
 • Ashima Malik et al. “Wildfire Risk Prediction and Detection using Machine Learning in San Diego, California”. In: Oct. 2021. 
 •https://www.kaggle.com/datasets/ananthu017/californiawildfire-incidents-20132020 
 • M. E. Alsahaft, M. A. Alharthi and M. Arif, "Role of Machine Learning Algorithms in Forest Fire Management: A Literature Review", J. Robot. Autom., vol. 5, pp. 212-226, February 2018. 
 • S. Youssef and B. Abdelaziz, "Prediction of Forest Fires Using Artificial Neural Networks", Appl. Math. Sci., vol. 7, pp. 271-286, January 2013
