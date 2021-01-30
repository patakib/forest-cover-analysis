# forest cover analysis

### Overview
This is a data science project in the topic of forestry.  
  
The dataset is available on [Kaggle](https://www.kaggle.com/uciml/forest-cover-type-dataset).  
This is a machine learning project, where the task is to predict the relevant tree species based on environment conditions in the given area.  
The dataset contains around 500k records, there are numerical and categorical features as well.  
  
### Result and Discussion
I tried different algorithms (with hyperparameter-tuning) for this project, such as SVC, KNN, Naive Bayes, Decision Tree, Random Forest. I also analyzed the confusion matrixes.   
K Nearest Neighbors had the best accuracy, around 80%, but all the others (after Grid Search) were between 70 and 75% (except of Naive Bayes which was way below this value).    

### Real-world Application
The method can be applied in real world when forest management companies are planning reforestations/afforestations.  
  
### Further Ideas
The method can be improved with meteorological data and predictions. As the climate is changing and the forestry sector plans for decades and centuries, the change in environmental conditions is important from the model perspective.  
In other words, where the conditions are perfect for a specific species now, the situation can be different in 30 years. Therefore if we could add predicted meterological data, it would be even better.

### Link to Code on Kaggle:
https://www.kaggle.com/blintpataki/forest-cover
