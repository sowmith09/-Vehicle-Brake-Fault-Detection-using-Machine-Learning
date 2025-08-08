# -Vehicle-Brake-Fault-Detection-using-Machine-Learning

 Description:Built a machine learning system to detect and classify vehicle brake faults using sensor 
data.Handled data cleaning, EDA, feature engineering, and trained multiple classification models.
Deployed 
the best model with a Streamlit UI for real-time fault prediction and maintenance insights.
Analyzed vehicle brake system sensor data containing pressure, hydraulic values, ABS status, and 
temperature to identify and classify brake faults.
Target variable: Fault – a multi-class label indicating different types of braking system faults or "No Fault", 
with the goal of enabling predictive maintenance.
Cleaned the dataset by handling missing values, removing duplicate entries, and ensuring consistent data 
types to maintain training integrity.
Performed Exploratory Data Analysis (EDA) using bar plots, histograms, box plots, and heatmaps to uncover 
feature relationships, detect outliers, and identify class imbalance. 
Features Engineering (e.g., pressure difference between wheels), applied one-hot encoding for categorical 
features like ABS_Status, and performed feature scaling for consistent model performance.
Trained and evaluated multiple ML models (Logistic Regression, Linear Regression) using metrics like 
Accuracy, Precision, Recall, F1-Score,deployed the best model using Streamlit with live predictions via 
Hugging Face Spaces.
