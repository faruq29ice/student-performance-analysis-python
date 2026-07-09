# Student Performance Analysis Using Python

## Exploratory Data Analysis (EDA)

Author: Adebiyi Faruq

Date: 6/9/2026

Tools:
- Python
- Pandas
- Matplotlib
- Seaborn

  
## Project Overview

This project explores the factors that influence students' academic performance using Python and Exploratory Data Analysis (EDA).

The analysis investigates how study habits, attendance, sleep patterns, internet usage, assignment completion, and previous academic performance relate to students' examination scores and placement outcomes.

The objective is to uncover meaningful insights that can help educational institutions make informed decisions to improve student success.



##  Business Problem

Educational institutions often seek to understand the factors that contribute to students' academic success and employability.

This project aims to answer the following questions:

- Does studying longer improve examination scores?
- Does attendance influence examination performance?
- Does sleep duration affect academic performance?
- Does internet usage impact examination scores?
- Does completing more assignments improve performance?
- Can previous academic performance predict future examination scores?
- What characteristics are common among students who were successfully placed?
- Which factor has the strongest relationship with examination performance?



##  Dataset

The dataset contains information on **10,000 students**, including:

- Study Hours
- Attendance
- Sleep Hours
- Internet Usage
- Assignments Completed
- Previous Academic Score
- Final Examination Score
- Placement Status



##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn


##  Project Workflow

### 1. Data Loading
- Imported the dataset into Pandas
- Inspected dataset structure

### 2. Data Cleaning
- Checked for missing values
- Checked duplicate records
- Verified data types
- Examined data quality
- Identified potential outliers

### 3. Exploratory Data Analysis (EDA)

Performed:

- Descriptive Statistics
- Histograms
- Scatter Plots
- Correlation Analysis
- Correlation Heatmap
- Group Comparisons



##  Key Findings

###  Study Hours had the strongest relationship with examination performance.

Students who studied longer generally achieved higher examination scores.

**Correlation:** **0.56**



###  Assignment completion positively influenced academic performance.

Students who completed more assignments tended to obtain higher examination scores.

**Correlation:** **0.39**



###  Previous academic performance was associated with future performance.

Students with higher previous scores generally achieved higher examination scores.

**Correlation:** **0.32**



###  Attendance had a positive relationship with examination scores.

Although weaker than study hours, students with better attendance generally performed better academically.

**Correlation:** **0.22**



###  Internet usage showed a weak negative relationship.

Higher internet usage was slightly associated with lower examination scores.

**Correlation:** **-0.15**



###  Successfully placed students demonstrated stronger academic habits.

Compared to students who were not placed, placed students:

- Studied more hours
- Had better attendance
- Completed more assignments
- Had higher previous scores
- Achieved significantly higher examination scores
- Spent slightly less time using the internet



##  Recommendations

Based on the analysis:

- Encourage students to maintain consistent study schedules.
- Promote timely assignment completion.
- Improve attendance through student engagement initiatives.
- Provide academic support for students with lower previous performance.
- Encourage responsible internet usage and effective time management.



##  Visualizations Included

The project includes:

- Distribution Histograms
- Scatter Plots
- Correlation Matrix
- Correlation Heatmap

These visualizations were used to identify trends and relationships within the dataset.



##  Project Structure

```
Student-Performance-Analysis/
│
├── student_dataset_analysis.ipynb
├── student_performance.csv
├── README.md

```



##  How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/faruq29ice/student-performance-analysis.git
```

2. Navigate into the project folder

```bash
cd student-performance-analysis
```

3. Install the required libraries

```bash
pip install pandas matplotlib seaborn
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open

```
student_dataset_analysis.ipynb
```



##  Skills Demonstrated

This project demonstrates proficiency in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Business Problem Solving
- Statistical Interpretation
- Python Programming
- Pandas
- Matplotlib
- Seaborn



##  Lessons Learned

Through this project, I strengthened my ability to:

- Clean and inspect real-world datasets
- Perform exploratory data analysis
- Create meaningful visualizations
- Interpret statistical relationships
- Translate business questions into data-driven insights
- Present analytical findings in a professional manner




##  Future Improvements

Possible extensions of this project include:

- Building machine learning models to predict examination scores.
- Predicting student placement using classification algorithms.
- Developing an interactive dashboard using Streamlit or Power BI.
- Performing feature importance analysis.
- Hyperparameter tuning and model evaluation.



##  License

This project is intended for educational and portfolio purposes.
