**Customer Churn Prediction using Decision Tree**

📌**Project Description:**

    This is a machine learning project that focuses on building a decision tree classifier to predict whether a customer will complain based on various features, such as satisfaction score, balance, and card type.
    The high accuracy is likely due to strong patterns in the dataset and is not generalizable to real-world churn prediction tasks.
    This is for academic and demo purposes only and does not represent production-ready churn models.
  
✅**Steps Performed**

    Data Collection:
        Loaded the dataset (customer-Churn-Records.csv) containing email features and labels.

    Data Cleaning:
        Checked for null values
        Handled outliers using the IQR method
        Removed unnecessary features like RowNumber,Surname,Complain and CustomerId

    Data Visualization:
        Used histograms to explore distributions
        Count plot for label distribution (churn vs not churn)

    Data Preprocessing:
        Split the dataset into training and testing sets

    Model Selection & Training:
        Used DecisionTreeClassifier
        Evaluated the model with classification metrics and a confusion matrix

📊 **Libraries Used**

    pandas
    numpy
    matplotlib
    seaborn
    scikit-learn
