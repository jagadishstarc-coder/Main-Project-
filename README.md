# Main-Project-
# 📊 Employee Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing and cleaning an **Employee Dataset** to extract meaningful insights related to employee demographics, departments, salaries, performance, employment status, and remote work.

The project demonstrates practical **Data Analytics skills** using real-world employee data and provides insights that can support better HR and business decision-making.

---

## 📂 Dataset

**File:** `Main Project Raw Data.csv`

### Dataset Details

* **Total Records:** 1,020 employees
* **Total Columns:** 12
* **Data Type:** Employee / HR Analytics Dataset

### 📋 Columns

| Column              | Description                                   |
| ------------------- | --------------------------------------------- |
| `Employee_ID`       | Unique employee identification number         |
| `First_Name`        | Employee first name                           |
| `Last_Name`         | Employee last name                            |
| `Age`               | Employee age                                  |
| `Department_Region` | Department and region of the employee         |
| `Status`            | Current employment status                     |
| `Join_Date`         | Employee joining date                         |
| `Salary`            | Employee salary                               |
| `Email`             | Employee email address                        |
| `Phone`             | Employee contact number                       |
| `Performance_Score` | Employee performance rating                   |
| `Remote_Work`       | Indicates whether the employee works remotely |

---

## 🎯 Project Objectives

The main objectives of this project are:

* Clean and prepare raw employee data
* Identify missing and duplicate values
* Analyze employee demographics
* Analyze salary distribution
* Compare salaries across departments and regions
* Analyze employee performance
* Examine employee employment status
* Analyze remote-work trends
* Generate meaningful business insights
* Build interactive dashboards and visualizations

---

## 🛠️ Tools & Technologies

* 🐍 **Python**
* 📊 **Pandas**
* 📈 **Matplotlib**
* 📉 **Seaborn**
* 📗 **Microsoft Excel**
* 💻 **SQL / MySQL**
* 📊 **Power BI**
* 📝 **Jupyter Notebook / Google Colab**

---

## 🔄 Data Analysis Process

### 1. Data Collection

Imported the raw employee dataset from a CSV file.

### 2. Data Cleaning

The dataset was checked for:

* Missing values
* Duplicate records
* Incorrect data types
* Formatting issues
* Invalid values
* Date formatting
* Salary and numerical data consistency

### 3. Data Transformation

Performed transformations such as:

* Converting dates into proper date format
* Extracting department and region information
* Creating calculated fields
* Categorizing employee information
* Preparing data for visualization

### 4. Exploratory Data Analysis

Analyzed:

* Employee count
* Age distribution
* Salary distribution
* Department-wise employees
* Region-wise employees
* Performance ratings
* Employment status
* Remote vs. non-remote employees

### 5. Visualization

Created charts and dashboards to identify trends and patterns in the employee data.

---

## 📊 Key Analysis Areas

### 👥 Employee Analysis

* Total number of employees
* Employees by department
* Employees by region
* Age distribution
* Employment status distribution

### 💰 Salary Analysis

* Average salary
* Minimum and maximum salary
* Department-wise salary comparison
* Region-wise salary comparison
* Salary distribution

### ⭐ Performance Analysis

* Performance rating distribution
* Performance by department
* Salary vs. performance
* Identification of high-performing employees

### 🏠 Remote Work Analysis

* Remote vs. non-remote employees
* Remote work by department
* Remote work by region
* Relationship between remote work and employee performance

---

## 📈 Dashboard

The project can be presented through an interactive **Power BI / Excel dashboard** containing:

* Total Employees
* Average Salary
* Average Age
* Active Employees
* Remote Employees
* Department-wise Employee Count
* Salary by Department
* Performance Distribution
* Employment Status
* Remote Work Analysis

---

## 💡 Business Insights

This analysis can help HR and management teams to:

* Understand workforce distribution
* Identify salary trends
* Monitor employee performance
* Compare departments and regions
* Understand remote-work adoption
* Support workforce planning
* Improve HR decision-making
* Identify areas requiring further investigation

---

## 📁 Project Structure

```text
Employee-Data-Analysis/
│
├── Main Project Raw Data.csv
├── Employee_Data_Analysis.ipynb
├── PowerBI_Dashboard.pbix
├── README.md
│
└── Screenshots/
    └── dashboard.png
```

---

## 🚀 How to Use

### Clone the Repository

```bash
git clone https://github.com/your-username/Employee-Data-Analysis.git
```

### Open the Dataset

Load:

```text
Main Project Raw Data.csv
```

using Python, Excel, SQL, or Power BI.

### Python Example

```python
import pandas as pd

df = pd.read_csv("Main Project Raw Data.csv")

print(df.head())
print(df.info())
print(df.describe())
```

---

## 🧹 Basic Data Cleaning Example

```python
# Check missing values
df.isnull().sum()

# Check duplicate records
df.duplicated().sum()

# Remove duplicate records
df = df.drop_duplicates()

# Check dataset information
df.info()
```

---

## 📊 Sample Analysis

### Average Salary

```python
df["Salary"].mean()
```

### Employee Count by Status

```python
df["Status"].value_counts()
```

### Performance Distribution

```python
df["Performance_Score"].value_counts()
```

### Remote Work Distribution

```python
df["Remote_Work"].value_counts()
```

---

## 🎓 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Excel
* Python
* Pandas
* Data Visualization
* SQL
* Power BI
* Dashboard Development
* Business Insights
* HR Analytics

---

## 👨‍💻 Author

**Jagadishwaran R**

Aspiring Data Analyst | HR Professional | Data Analytics Enthusiast

### 🔗 Connect With Me

* **LinkedIn:** [Jagadishwaran R](https://www.linkedin.com/in/jagadishwaran-r-139333245/)
* **GitHub:** [jagadishstarc-coder](https://github.com/jagadishstarc-coder)

---

## ⭐ Project Goal

> **Turning employee data into meaningful insights to support smarter HR and business decisions.**

If you find this project useful, please consider giving the repository a ⭐.
