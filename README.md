# Student Academic Performance and Student Dropout Risk Analysis

## Project Overview

The **Student Academic Performance and Student Dropout Risk Analysis** project focuses on analyzing student academic data using Python. It uses statistical methods and data visualization to understand academic performance, attendance patterns, semester-wise GPA, and the distribution of student dropout labels.

The project is developed using Jupyter Notebook and Python libraries for data analysis and visualization.

## Objectives

- To analyze student academic performance using a dataset.
- To compare GPA across different semesters.
- To examine the relationship between attendance and academic performance.
- To analyze the distribution of student dropout labels.
- To visualize patterns using different types of graphs.
- To calculate descriptive statistics and correlations between numerical attributes.
- To present meaningful observations from the dataset.

## Dataset Description

**Dataset name:** `student_dropout_risk_2026.csv`

The dataset contains student-related academic and behavioral attributes, including:

- Age
- Attendance rate
- Assignment submission rate
- GPA for Semester 1
- GPA for Semester 2
- Course type
- Number of failed units
- Missed deadlines
- Stress level
- Satisfaction score
- Dropout label

The dataset contains 100,000 records and 34 columns, according to the notebook's saved analysis output.

## Technologies Used

- **Python** — Programming language
- **Jupyter Notebook** — Development environment
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical calculations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization

## Data Analysis and Visualization

The project explores the dataset using descriptive statistics, grouping, and correlation analysis.

Visualizations include:

1. Distribution of dropout labels
2. GPA comparison across semesters
3. Attendance comparison by dropout status
4. Attendance distribution
5. Dropout-label percentage by course type
6. Attendance versus Semester 2 GPA scatter plot
7. Correlation heatmap

## Data Cleaning

The notebook's saved output reports:

- Missing values: 0
- Duplicate records: 0

These checks help assess the completeness and consistency of the dataset.

## Key Observations

- The dataset contains 100,000 student records and 34 columns.
- A total of 32,004 records are labelled `dropout = 1`, while 67,996 are labelled `dropout = 0`.
- The records labelled `dropout = 1` represent 32.00% of the dataset.
- The average attendance rate is approximately 75.1%.
- The average Semester 2 GPA is approximately 1.98.

These observations describe the available dataset and should not be interpreted as proof that any particular factor causes dropout.

## How to Run the Project

### 1. Download or clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Student-Academic-Performance-Analysis.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Open the project folder

Open the downloaded folder in Visual Studio Code or Jupyter Notebook.

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Check the dataset path

Place `student_dropout_risk_2026.csv` in the same folder as the notebook, if you are permitted to redistribute the dataset.

Load it using:

```python
import pandas as pd

data = pd.read_csv("student_dropout_risk_2026.csv")
```

If the dataset is not included in the repository, obtain it from its original source and update the file path accordingly.

### 5. Run the notebook

Open `miniproject1_vsec.ipynb` in VS Code or Jupyter Notebook and execute the cells in order.

## Project Files

- `miniproject1_vsec.ipynb` — Notebook containing the analysis and visualizations.
- `student_dropout_risk_2026.csv` — Dataset, if permitted to share.
- `Student_Academic_Performance_Report.docx` — Project report, if included.
- `README.md` — Project description and instructions.

## Conclusion

This project demonstrates how Python libraries can be used to explore student academic data through descriptive statistics and visualizations. It provides insights into GPA, attendance, and dropout-label patterns that may support further investigation into student performance.

The findings show associations and descriptive patterns in the dataset; they do not establish causal relationships.

## Author

**Student Academic Performance and Student Dropout Risk Analysis**

## References

- [Python Documentation](https://docs.python.org/3/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
