# Student Score Analysis

This project analyzes a dataset of student scores to uncover trends and relationships between various factors such as gender, parental education, and co-curricular activities. The analysis focuses on understanding how these factors impact student performance and provides key insights through data visualization.

---

## **Project Highlights**

### **Goals**
1. Explore the distribution of student scores.
2. Analyze how gender and parental education affect scores.
3. Study the influence of lunch type and co-curricular activities on performance.
4. Detect outliers and understand ethnic group distribution's role in scoring patterns.

---

## **Analysis Workflow**

### **1. Data Cleaning**
- Removed unnecessary columns and handled missing values.
- Deleted the "Unnamed" column from the dataset.

### **2. Exploratory Data Analysis (EDA)**
- **Gender Analysis**: Analyzed the male-to-female ratio and its impact on scores.
- **Parental Education**: Studied how parents' education levels correlate with student performance.
- **Lunch Type**: Investigated the relationship between lunch type (standard vs. free/reduced) and scores.
- **Co-curricular Activities**: Measured the impact of participation in activities on performance.
- **Outliers**: Identified and handled outliers in the dataset for more accurate analysis.

---

## **Key Insights**
1. **Gender Impact**: Gender does not significantly influence overall performance, but subtle differences exist in specific score categories.
2. **Parental Education**: Higher parental education correlates with better student performance.
3. **Lunch Type**: Students with standard lunch types tend to perform better compared to those with free/reduced lunches.
4. **Co-curricular Activities**: Participation in co-curricular activities positively impacts scores, especially in critical subjects.
5. **Ethnic Group Analysis**: Certain ethnic groups show distinct scoring patterns, likely influenced by external factors.

---

## **Results**
- **Top Performers**: Identified the highest-scoring students and their characteristics.
- **Score Trends**: Created visualizations showcasing performance trends across gender, parental education, and other factors.
- **Outlier Detection**: Highlighted irregular data points for further investigation.

---

## **Sample Visualizations**
The notebook includes various visualizations to support the analysis, such as:
- Bar charts for gender distribution.
- Scatter plots for parental education vs. scores.
- Box plots for lunch type and co-curricular activity analysis.

---

## **Getting Started**

### Prerequisites
- Python 3.7+ installed.
- Required libraries:
  ```bash
  pip install numpy pandas matplotlib seaborn
