# Social Media Content Analysis Using Python

## 📌 Project Overview

This project analyzes social media content data using **Python** to understand platform distribution, content types, engagement patterns, and content performance.

The project focuses on **data cleaning, data preprocessing, exploratory data analysis (EDA), and data visualization** using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

The objective is to transform raw social media data into meaningful insights that can help understand content trends and audience engagement.

---

## 🎯 Objectives

* Clean and preprocess the raw social media dataset.
* Analyze social media platforms.
* Analyze different content types.
* Understand engagement patterns.
* Compare content performance.
* Identify high-performing content.
* Visualize important trends and patterns.
* Generate meaningful insights from social media data.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Google Colab**
* **CSV/Excel** – Dataset source

---

## 📊 Dataset

The dataset contains information about social media content and its performance.

The data includes attributes related to:

* Social media platforms
* Content types
* Posts
* Engagement
* Likes
* Comments
* Shares
* Reach
* Impressions
* Other content performance metrics

### Dataset Size

* **Original dataset:** 2,012 rows × 15 columns
* **Final cleaned dataset:** 2,000 rows × 17 columns

The dataset was cleaned and transformed using Python before performing exploratory data analysis.

---

## 🧹 Data Cleaning & Preprocessing

The raw dataset was loaded into Google Colab using Pandas.

The following data-cleaning steps were performed:

* Loaded the dataset.
* Inspected the dataset structure.
* Checked rows and columns.
* Identified missing values.
* Checked duplicate records.
* Cleaned inconsistent values.
* Standardized data.
* Created additional columns where required.
* Verified the cleaned dataset.
* Prepared the final dataset for analysis.

---

## 🐍 Python Implementation

### Import Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

### Load Dataset

```python
df = pd.read_csv("social_media_data.csv")
```

### Inspect Dataset

```python
df.head()
```

```python
df.shape
```

```python
df.info()
```

### Check Missing Values

```python
df.isnull().sum()
```

### Check Duplicate Records

```python
df.duplicated().sum()
```

---

## 🔎 Exploratory Data Analysis

Exploratory Data Analysis was performed to identify patterns and trends in the social media dataset.

The analysis focused on:

* Platform distribution
* Content-type distribution
* Engagement analysis
* Content performance
* Platform comparison
* High-performing content
* Statistical summaries
* Data visualization

---

## 📱 Platform Analysis

The cleaned dataset contains posts from different social media platforms.

The major platforms identified in the dataset include:

| Platform  | Number of Posts |
| --------- | --------------: |
| Instagram |             939 |
| YouTube   |             417 |
| Facebook  |             358 |

This analysis helps understand the distribution of content across different social media platforms.

---

## 🎬 Content Type Analysis

The project also analyzes the different types of social media content.

The cleaned dataset contains content types such as:

| Content Type | Number of Posts |
| ------------ | --------------: |
| Image        |             493 |
| Carousel     |             367 |
| Video        |               8 |
| Reel         |               8 |
| Story        |               1 |

This analysis helps identify the most frequently used content formats.

---

## ❤️ Engagement Analysis

Engagement metrics were analyzed to understand how users interact with social media content.

Important metrics analyzed include:

* Likes
* Comments
* Shares
* Engagement
* Reach
* Impressions

The analysis helps identify patterns in audience interaction and determine which content performs better.

---

## 📈 Data Visualization

Python visualization libraries were used to represent the findings graphically.

### Matplotlib

Used for:

* Bar charts
* Line charts
* Distribution plots
* Comparative visualizations

### Seaborn

Used for:

* Statistical visualizations
* Relationship analysis
* Distribution analysis
* Heatmaps

---

## 💡 Key Business Insights

The analysis helps answer questions such as:

* Which platform has the highest number of posts?
* Which content type is most frequently used?
* Which platform receives higher engagement?
* Which content type performs better?
* Which posts generate higher interaction?
* How does engagement vary across platforms?
* How does content format affect performance?
* What type of content should receive more attention?

These insights can help businesses understand their social media performance and improve their content strategy.

---

## 🧠 Business Problem

Businesses publish content across multiple social media platforms, but it can be difficult to determine which platforms and content types perform better.

This project uses Python-based data analysis to understand:

* Platform performance
* Content distribution
* Audience engagement
* Content performance
* Engagement trends

The results can help businesses make more informed decisions about their social media content strategy.

---

## 🔄 Project Workflow

```text
Raw Social Media Dataset
          ↓
Data Loading
          ↓
Data Inspection
          ↓
Data Cleaning
          ↓
Data Preprocessing
          ↓
Exploratory Data Analysis
          ↓
Data Visualization
          ↓
Platform Analysis
          ↓
Content Analysis
          ↓
Engagement Analysis
          ↓
Business Insights
```

---

## 📁 Project Structure

```text
Social-Media-Content-Analysis/
│
├── README.md
│
├── Social_Media_Content_Analysis.ipynb
│
├── Dataset/
│   ├── raw_social_media_data.csv
│   └── cleaned_social_media_data.csv
│
└── Images/
    ├── platform_distribution.png
    ├── content_type_distribution.png
    └── engagement_analysis.png
```

---

## ▶️ How to Run the Project

### Step 1 — Open the Python Notebook

Open:

```text
Social_Media_Content_Analysis.ipynb
```

The notebook contains the complete Python analysis.

### Step 2 — Open in Google Colab

Upload the notebook to Google Colab or open it directly from GitHub.

### Step 3 — Add the Dataset

Place the dataset in the same working environment as the notebook.

### Step 4 — Run the Notebook

Run the cells sequentially to perform:

* Data loading
* Data cleaning
* Data preprocessing
* Exploratory analysis
* Visualization
* Insight generation

---

## 🧪 Python Libraries Used

### Pandas

Used for:

* Data loading
* Data cleaning
* Data manipulation
* Data transformation
* Grouping and aggregation

### NumPy

Used for:

* Numerical calculations
* Data transformation
* Mathematical operations

### Matplotlib

Used for:

* Creating charts
* Comparing categories
* Visualizing trends

### Seaborn

Used for:

* Statistical visualization
* Distribution analysis
* Relationship analysis
* Heatmaps

---

## 🧠 Skills Demonstrated

### Python

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Visualization
* GroupBy
* Aggregation
* Missing Value Analysis
* Duplicate Detection

### Analytical Skills

* Social Media Analytics
* Engagement Analysis
* Platform Analysis
* Content Performance Analysis
* Trend Analysis
* Data Interpretation
* Business Insight Generation

---

## ⭐ Key Takeaways

This project demonstrates a complete Python-based data analytics workflow:

**Raw Data → Data Cleaning → Data Preprocessing → EDA → Visualization → Insights**

Python was used to clean, analyze, visualize, and interpret social media data to identify meaningful patterns in platforms, content types, and engagement.

---

## 👩‍💻 Author

**Sonah**

Data Analytics Project

**Skills:** Python | SQL | Power BI | Excel | Data Analysis
