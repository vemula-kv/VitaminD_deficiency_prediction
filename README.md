This project develops a machine learning model to predict Vitamin D deficiency levels ('Normal', 'Mild Deficiency', 'Severe Deficiency') using a dataset with 47 clinical and biochemical features, such as Age, Gender, Glucose, HbA1c, and blood count metrics. The dataset contains significant missing values (e.g., Iron_Binding: 632, CK: 652), which are handled using SimpleImputer. Exploratory data analysis is performed with visualizations like heatmaps for feature correlations, pairplots for feature relationships, and class distribution graphs to understand the target variable's distribution. The data is split into training and testing sets to evaluate model performance.



Multiple machine learning models—Random Forest, XGBoost, AdaBoost, and a Neural Network—were trained and compared, with the XGBoost Classifier selected for its superior accuracy in classifying Vitamin D deficiency levels. The Jupyter notebook (VitaminD.ipynb) implements the entire pipeline, including data preprocessing, visualization, model training, and evaluation. Visualizations like confusion matrices and performance metrics (e.g., accuracy, precision) are included to assess the model. The project is hosted on GitHub, providing a reproducible framework for predicting Vitamin D deficiency using clinical data.

                 
