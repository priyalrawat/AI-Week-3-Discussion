# AI-Week-3-Discussion
Resolving classification problem with Machine Learning

**Problem Statement:**
Breast cancer is one of the most common cancers among women worldwide, and early diagnosis is critical for effective treatment and improving survival rates. The goal of this project is to create a machine learning model that accurately classifies breast tumors as malignant (cancerous) or benign (non-cancerous) using data. This Project aims to provide a reliable decision-support tool for diagnosing breast cancer based on patient data.

**Dataset description:**
The dataset includes 30 features categorized into three groups for each cell nucleus characteristic:
1.	Mean values (e.g., mean radius, mean texture).
2.	Standard errors (e.g., radius error, texture error).
3.	Worst values (e.g., worst radius, worst area).
Target Variable: The target variable is diagnosis, which indicates whether a tumor is malignant (1) or benign (0)

**Approach:**
The detailed steps followed to build the machine learning model is in the jupyter notebook, step by step right from the start. I have used Logistic Regression for this project as it is simple to use in binary classification problems. 

**Evaluation of the model:**
The model's performance was evaluated using the following metrics:
•	Accuracy Score: Measures the percentage of correctly classified samples.
•	Classification Report: Provides detailed metrics such as precision, recall, and F1-score for each class.
•	Confusion Matrix: Displays the number of true positives, true negatives, false positives, and false negatives, offering a more nuanced view of the model's predictions.

**Results (Key outcomes):**
	95% Accuracy
	Classification Report that includes Precision showed High precision values for both classes indicate that the model has a low false positive rate, Recall showed High recall values suggest that the model successfully identifies most malignant and benign cases, and F1-Score showed Balanced precision and recall, confirming the model’s robustness.
	The confusion matrix demonstrated very few misclassifications, affirming the model's reliability. (Figure 1)

Figure 1: ![Figure 2025-01-29 141340](https://github.com/user-attachments/assets/39ef6442-1eaa-43c8-b2cb-cc7450ac2207)

**Benefits of this model in the real world:**
	Early Detection
	Decision Support making informed decisions
	Scalability
	Automation

By leveraging this machine learning model, healthcare providers can enhance diagnostic accuracy, save time, and ultimately improve patient outcomes.
