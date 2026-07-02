# Data-Cleaning-in-Pandas
# 📞 Customer Call List Data Cleaning Using Pandas

## 🚀 Overview

This project focuses on cleaning and preparing a customer call list dataset using Python and Pandas. Real-world datasets often contain missing values, duplicate records, inconsistent formatting, and invalid entries. The objective of this project is to transform raw customer data into a clean and analysis-ready dataset.

The project demonstrates essential data cleaning techniques that are widely used in Data Analysis, Data Engineering, and Business Intelligence projects.

---

# 🎯 Project Objectives

* Clean messy customer data.
* Remove duplicate records.
* Handle missing values.
* Standardize text formats.
* Correct inconsistent phone numbers.
* Prepare data for analysis and reporting.

---

# 🏗️ Architecture

```text id="b4m7q2"
Raw Customer Dataset
          │
          ▼
     Pandas DataFrame
          │
          ▼
    Data Cleaning
          │
          ▼
 Data Transformation
          │
          ▼
 Clean Dataset
          │
          ▼
 Analysis & Reporting
```

---

# 🛠️ Tech Stack

## Programming Language

* Python

## Libraries Used

* Pandas
* NumPy

## Development Tools

* Jupyter Notebook
* VS Code
* Git
* GitHub

---

# 📂 Dataset Information

The dataset contains customer contact information used for call campaigns.

### Sample Columns

```text id="h9v3k6"
Customer_ID
First_Name
Last_Name
Phone_Number
Address
Email
Do_Not_Contact
Not_Useful_Column
```

---

# ⚙️ Data Cleaning Workflow

## Step 1: Load Dataset

Import customer call list data into a Pandas DataFrame.

### Example

```python id="n2x8r5"
import pandas as pd

df = pd.read_csv("Customer Call List.csv")
```

---

## Step 2: Remove Duplicates

Duplicate customer records are identified and removed.

### Benefits

* Improved data quality
* Reduced redundancy
* Accurate reporting

---

## Step 3: Drop Unnecessary Columns

Remove irrelevant columns that do not contribute to analysis.

### Example

* Not_Useful_Column

---

## Step 4: Clean Text Fields

Standardize customer names and other text columns.

### Tasks Performed

* Remove extra spaces
* Remove special characters
* Fix capitalization issues

---

## Step 5: Clean Phone Numbers

Transform phone numbers into a consistent format.

### Example

```text id="p5d1s7"
(123)-456-7890
123.456.7890
1234567890
```

Converted to:

```text id="t8k4m1"
123-456-7890
```

---

## Step 6: Handle Missing Values

Managed null and blank values using Pandas functions.

### Techniques Used

* Fill Missing Values
* Replace Empty Strings
* Remove Invalid Records

---

## Step 7: Filter Records

Exclude customers who should not be contacted.

### Example

Remove customers marked as:

```text id="r3c7n2"
Do_Not_Contact = Yes
```

---

## Step 8: Export Clean Data

Save the cleaned dataset for future use.

### Example

```python id="z7m9v4"
df.to_csv("clean_customer_data.csv", index=False)
```

---

# 📊 Data Cleaning Tasks Performed

✔ Removed Duplicate Records

✔ Dropped Unnecessary Columns

✔ Cleaned Customer Names

✔ Standardized Phone Numbers

✔ Handled Missing Values

✔ Removed Invalid Records

✔ Filtered Non-Contactable Customers

✔ Exported Clean Dataset

---

# 🔑 Pandas Functions Used

### Data Loading

* read_csv()

### Data Inspection

* head()
* info()
* describe()

### Data Cleaning

* drop_duplicates()
* drop()
* replace()
* fillna()
* str.replace()
* str.strip()

### Data Filtering

* loc[]
* isin()

### Exporting Data

* to_csv()

---

# 📈 Skills Demonstrated

## Data Cleaning

* Data Quality Improvement
* Missing Value Handling
* Duplicate Removal
* Data Standardization

## Python

* Pandas
* NumPy

## Data Processing

* Data Transformation
* Data Validation
* Data Preparation

## Analytics

* Dataset Preparation
* Reporting Readiness

---

# 📁 Project Structure

```text id="g6n4w8"
Customer-Call-List-Data-Cleaning/

│
├── data/
│   ├── Customer_Call_List.csv
│
├── notebooks/
│   ├── customer_call_list_cleaning.ipynb
│
├── cleaned_data/
│   ├── clean_customer_data.csv
│
├── screenshots/
│   ├── before_cleaning.png
│   ├── after_cleaning.png
│
├── README.md
│
├── requirements.txt
│
└── LICENSE
```

---

# 💡 Business Use Cases

* Customer Relationship Management (CRM)
* Marketing Campaigns
* Call Center Operations
* Customer Outreach Programs
* Sales Lead Management
* Data Quality Management

---

# 📊 Sample Questions Answered

1. How can duplicate customer records be removed?
2. How can phone numbers be standardized?
3. How can missing customer information be handled?
4. How can customer contact lists be cleaned before campaigns?
5. How can non-contactable customers be filtered out?

---

# 🚀 Future Enhancements

* Automate data cleaning pipelines.
* Add email validation.
* Integrate SQL databases.
* Build data quality dashboards.
* Implement customer segmentation.
* Deploy as a reusable data-cleaning application.

---

# 🎓 Learning Outcomes

Through this project, I gained hands-on experience in:

* Data Cleaning with Pandas
* Data Validation Techniques
* Missing Value Handling
* Text Processing
* Data Transformation
* Dataset Preparation for Analysis
* Real-World Data Quality Challenges

---

# 👨‍💻 Author

**Umesh Kumawat**

Aspiring Data Engineer | Data Analyst | B.Tech Computer Science

### Connect with Me

* LinkedIn: https://www.linkedin.com/in/umeshdaya2625/

---

## ⭐ Project Highlights

✔ Cleaned real-world customer contact data

✔ Applied essential Pandas data-cleaning techniques

✔ Standardized phone numbers and text fields

✔ Improved overall data quality

✔ Prepared data for business reporting and analysis

✔ Portfolio-ready project for Data Analyst and Data Engineer roles

---

⭐ If you found this project useful, consider giving it a star on GitHub.
