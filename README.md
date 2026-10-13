# Climate-Data-Analysis-and-Temperature-Prediction-Using-Machine-Learning
How can we use environmental data to predict daily temperature? In this project, I explored how machine learning can be applied to climate data to predict mean daily temperature (mean_temperature_c) using environmental measurements.

The goal was to build, evaluate, and compare different regression models to understand how well they predict temperature and how different modelling approaches perform on the same dataset.
This project was also an opportunity for me to strengthen my understanding of the complete machine learning workflow, from exploratory data analysis and feature selection to model evaluation and comparison.

🎯 Project Objectives
- Explore and understand the climate dataset through exploratory data analysis (EDA).
- Examine relationships between environmental variables and mean daily temperature.
- Apply feature selection using correlation analysis.
- Train and compare multiple regression models.
- Evaluate model performance using appropriate regression metrics.
- Use feature importance to understand which environmental variables contribute most to model predictions.
- Explore stacking as an ensemble learning technique.
🛠️ Tools and Technologies
- Python — programming and model development
- Pandas and NumPy — data manipulation and numerical operations
- Matplotlib and Seaborn — data visualization
- Scikit-learn — preprocessing, model training, and evaluation
- Jupyter Notebook — analysis and experimentation

🔍 Project Workflow
1. Exploratory Data Analysis: Inspected the dataset, reviewed descriptive statistics, plotted distributions, and explored relationships between variables.
2. Correlation Analysis: Examined correlations between environmental features and mean daily temperature.
3. Data Preprocessing: Separated the features from the target variable, split the data into training and testing sets, and applied Min-Max scaling.
4. Model Development: Trained and compared five approaches:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Stacking Regressor
5. Model Evaluation: Used R², Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) to evaluate predictive performance.
6. Model Interpretation: Compared actual and predicted temperatures, examined residuals, and explored feature importance.

📊 Results and Key Findings
The models were evaluated on the test dataset. The results recorded in my notebook were:
Model	R² Score	RMSE
Linear Regression	0.772	3.094
Decision Tree	0.826	2.698
Random Forest	0.856	2.455
Gradient Boosting	0.941	1.574
Stacking	0.886	2.186
The results show that Gradient Boosting performed best among the five models in this experiment, with an R² score of approximately 0.941 and an RMSE of 1.574.
Other important observations from the project:
- Gradient Boosting achieved the lowest prediction error among the tested models.
- Random Forest provided better test performance than Linear Regression and the Decision Tree model.
- Stacking did not outperform Gradient Boosting in this experiment.
- Feature importance analysis highlighted solar_radiation_w_m2 and day_of_year as the two most influential features in the Random Forest model.
Note: These results reflect this dataset and experimental setup; they do not establish how the models would perform on all climate datasets or future weather conditions.

💡 What I Learned
This project helped me develop practical experience in:
- Understanding the relationship between features and a target variable.
- Selecting features and interpreting model feature importance.
- Comparing linear models, tree-based models, and ensemble methods.
- Evaluating model performance using multiple metrics rather than relying on a single score.
- Using residual plots and actual-versus-predicted plots to investigate model behaviour.
- Understanding that a more complex model does not automatically guarantee the best performance.

🚀 Future Improvements
- Apply cross-validation and hyperparameter tuning.
- Investigate possible data leakage and improve validation for time-dependent climate observations.
- Compare predictions using additional datasets and unseen time periods.
- Further investigate model errors and feature contributions.
- Explore whether the model generalizes to different geographical locations and seasons.
📁 Project File
[Climate.ipynb](https://github.com/user-attachments/files/33385331/Climate.ipynb)

🤝 Feedback and Collaboration
I welcome feedback, suggestions, and discussions on improving this project, especially around regression modelling, ensemble learning, and climate data analysis.
This is part of my ongoing journey in data science, where I am learning to turn data into meaningful insights and build models that address practical problems.
#DataScience #MachineLearning #Python #ClimateData #Regression #ScikitLearn #DataAnalytics #LearningInPublic
