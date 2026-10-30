# Customer Churn Prediction Using Machine Learning

## About the Project

I built this project to understand how machine learning can be used to predict customer churn. Customer churn happens when customers stop using a company's services. By analysing customer data, businesses can identify customers who may be likely to leave and take steps to improve customer retention.

In this project, I used the Telco Customer Churn dataset to explore customer information, preprocess the data, train different machine learning models, and compare their performance.

## What I Worked On

- Explored the dataset and analysed customer information.
- Cleaned and prepared the data for machine learning.
- Converted categorical features into numerical values.
- Used SMOTE to address class imbalance.
- Trained and compared three machine learning models.
- Evaluated the models using accuracy, precision, recall, F1-score, ROC-AUC, and cross-validation.

## Machine Learning Models

I experimented with the following models:

- XGBoost Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

## Results

Among the three models, Gradient Boosting achieved the best overall results on the test set in my evaluation, with an accuracy of 78.21%, an F1-score of 63.84%, and a ROC-AUC score of 84.39%.

I also compared precision and recall to understand how well the models identified customers who churned. This helped me see why accuracy alone is not enough when evaluating a classification model, especially when the target classes are imbalanced.

## Tools and Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Imbalanced-learn, and Jupyter Notebook.

## Dataset

The project uses the Telco Customer Churn dataset, which contains 7,043 customer records and information about their services, contracts, payment methods, and churn status.

## How to Run

1. Download or clone this repository.
2. Install the required libraries using `requirements.txt`.
3. Open `Customer_Churn_Prediction.ipynb` in Jupyter Notebook or VS Code.
4. Make sure the CSV dataset is available at the file path used in the notebook.
5. Run the notebook cells in order.

## What I Learned

Through this project, I gained practical experience in data preprocessing, handling imbalanced data, training ensemble machine learning models, and comparing classification performance. I also learned how precision, recall, F1-score, and ROC-AUC provide different perspectives on a model's performance.

## Future Improvements

I would like to improve the model through further hyperparameter tuning, explore better ways to handle categorical features, and build a simple web application where users can test churn predictions.

