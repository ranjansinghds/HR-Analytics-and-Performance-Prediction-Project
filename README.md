# Human Resources Department Project

## 📌 Overview

This project focuses on analyzing employee data to gain insights into various human resources metrics. The goal is to understand factors affecting employee performance, satisfaction, and retention.

## 📂 Project Structure

```
├── Human_Resources_project_png/      # Visualizations generated during analysis
├── Human_Resources.csv               # Dataset containing employee information
├── Human_Resources_Department_Project.ipynb  # Jupyter Notebook with analysis and findings
├── README.md                         # Project documentation
```

## 📊 Dataset

The dataset, `Human_Resources.csv`, includes employee information with features such as:

- **Employee ID**: Unique identifier for each employee.
- **Age**: Employee's age.
- **Department**: Department in which the employee works.
- **Education**: Level of education attained.
- **Job Role**: Specific role or position of the employee.
- **Marital Status**: Marital status of the employee.
- **Years at Company**: Tenure of the employee within the company.
- **Job Satisfaction**: Self-reported job satisfaction level.
- **Performance Rating**: Performance evaluation score.

## 🚀 Installation

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/ranjansinghds/Human-Resource-Department-Project.git
cd Human-Resource-Department-Project
```

### 2️⃣ Install dependencies:

Ensure you have the following Python packages installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🔍 Methodology

### 1. **Data Preprocessing**

- **Handling Missing Values**: Identified and addressed any missing data in the dataset.
- **Encoding Categorical Variables**: Converted categorical features such as `Department`, `Education`, and `Job Role` into numerical representations.
- **Feature Scaling**: Standardized numerical features to ensure uniformity.

### 2. **Exploratory Data Analysis (EDA)**

- **Visualized distributions** of key features to understand data patterns.
- **Correlation Analysis**: Examined relationships between different features to identify potential predictors of employee satisfaction and performance.
- **Trend Analysis**: Investigated trends across departments, job roles, and other categorical variables.

### 3. **Model Building**

- **Predictive Modeling**: Developed machine learning models to predict employee performance ratings based on available features.
- **Model Evaluation**: Assessed model performance using metrics like accuracy, precision, recall, and F1-score.

## 📊 Visualizations

Here are some visualizations from the project:

  ![alt text](https://github.com/ranjansinghds/Human-Resource-Department-Project/blob/main/Human_Resources_Project_Png/Histogram.png)
  ![alt text](https://github.com/ranjansinghds/Human-Resource-Department-Project/blob/main/Human_Resources_Project_Png/boxplot%20of%20JobRole%20vs.%20Monthly%20Income.png)
  ![alt text](https://github.com/ranjansinghds/Human-Resource-Department-Project/blob/main/Human_Resources_Project_Png/boxplot.png)
  ![alt text](https://github.com/ranjansinghds/Human-Resource-Department-Project/blob/main/Human_Resources_Project_Png/Countplot_Age_Attrition.png)
  ![alt text](https://github.com/ranjansinghds/Human-Resource-Department-Project/blob/main/Human_Resources_Project_Png/Heatmap.png)
  ![alt text](https://github.com/ranjansinghds/Human-Resource-Department-Project/blob/main/Human_Resources_Project_Png/Kdeplot.png)
  ![alt text](https://github.com/ranjansinghds/Human-Resource-Department-Project/blob/main/Human_Resources_Project_Png/Subplot%20countplot_MaritalStatus_JobRole_JobInvolvement_JobLevel_Attrition.png)

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

## 📌 Future Improvements

- **Advanced Predictive Models**: Implement more complex models to improve prediction accuracy.
- **Employee Retention Analysis**: Extend the analysis to understand factors influencing employee retention.
- **Interactive Dashboards**: Develop dashboards to allow dynamic exploration of HR metrics.