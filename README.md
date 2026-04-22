Employee Attrition Prediction
Predicting which employees are likely to leave an organization using HR data and a Logistic Regression baseline model.

1. Project Overview
This project analyzes an HR attrition dataset and builds a baseline classification model to predict whether an employee is likely to leave the company (attrition). The workflow covers data understanding, feature selection, model training, and packaging of key artifacts (dataset, notebook, model, report, and requirements).

The work is organized in the GitHub repository:
https://github.com/vivek-bhushan/IIT-M

2. Dataset
File: WA_Fn-UseC_-HR-Employee-Attrition.csv

Source (GitHub):
https://github.com/vivek-bhushan/IIT-M/blob/main/WA_Fn-UseC_-HR-Employee-Attrition.csv

The dataset contains HR-related information for employees. Important features include:

Age

MonthlyIncome

DistanceFromHome

The target variable is whether the employee has left the organization (attrition).

3. Modeling Approach
Baseline model: Logistic Regression

Task: Binary classification – predict if an employee is likely to leave or stay.

Reason for choice: Logistic Regression provides a simple, interpretable baseline for understanding how features such as Age, MonthlyIncome, and DistanceFromHome relate to attrition.

More detailed analysis, feature engineering, and model training steps are documented in the notebook and report.

4. Repository Contents
The main artifacts for this project are stored in the IIT-M repository:

Dataset (CSV) – WA_Fn-UseC_-HR-Employee-Attrition.csv
https://github.com/vivek-bhushan/IIT-M/blob/main/WA_Fn-UseC_-HR-Employee-Attrition.csv

Model artifact (PKL) – model.pkl
https://github.com/vivek-bhushan/IIT-M/blob/main/model.pkl

Notebook (IPYNB) – notebook.ipynb
https://github.com/vivek-bhushan/IIT-M/blob/main/notebook.ipynb

Report (PDF) – report.pdf
https://github.com/vivek-bhushan/IIT-M/blob/main/report.pdf

Requirements (TXT) – requirements.txt
https://github.com/vivek-bhushan/IIT-M/blob/main/requirements.txt

Project folder (Week 7)
https://github.com/vivek-bhushan/IIT-M/tree/main

5. Direct Raw Download Links
If you prefer direct downloads (for scripts, automation, or quick access), use the raw links below:

Dataset (raw CSV)
https://raw.githubusercontent.com/vivek-bhushan/IIT-M/main/WA_Fn-UseC_-HR-Employee-Attrition.csv

Report (raw PDF)
https://raw.githubusercontent.com/vivek-bhushan/IIT-M/main/report.pdf

Model (raw PKL)
https://raw.githubusercontent.com/vivek-bhushan/IIT-M/main/model.pkl

Notebook (raw IPYNB)
https://raw.githubusercontent.com/vivek-bhushan/IIT-M/main/notebook.ipynb

Requirements (raw TXT)
https://raw.githubusercontent.com/vivek-bhushan/IIT-M/main/requirements.txt

6. Getting Started

6.1 Clone the repository
```bash
git clone https://github.com/vivek-bhushan/IIT-M.git
cd IIT-M
```
6.2 Install dependencies
```bash
pip install -r requirements.txt
```
6.3 Run the analysis notebook
Start Jupyter and open the notebook:

```bash
jupyter lab  # or: jupyter notebook
```
Then open notebook.ipynb and run the cells to reproduce the analysis, visualizations, and Logistic Regression model.

7. Results
The final notebook cell compares Logistic Regression and a decision tree model using F1 score and reports the confusion matrix for the best-performing model (Logistic Regression). The figure below shows the bar chart of model F1 scores and the confusion matrix for the Logistic Regression classifier.

7.1 Final model output screenshot: https://github.com/vivek-bhushan/IIT-M/blob/main/Final%20output%20Image.jpg

(Place Final output Image is in the root of the repository so this path is valid on GitHub.)

8. Possible Extensions
Some ideas to extend this project:

Compare Logistic Regression with additional tree-based or ensemble models (Random Forest, XGBoost).

Add more detailed feature engineering (e.g., interaction terms, scaling strategies).

Build a lightweight API or web app around the trained model for demonstration purposes.

9. Repository Link
Main repository:
https://github.com/vivek-bhushan/IIT-M