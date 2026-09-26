Student Performance Analysis

📌 Project Overview

This project presents a complete analysis of the Student Performance Dataset using Python.

The project combines Data Analysis, Statistics, Probability, Hypothesis Testing, Linear Algebra, and Calculus to understand student academic performance and demonstrate how mathematical concepts are connected to Machine Learning.

The final grade "G3" is used as the main target variable throughout the analysis.

---

🎯 Project Objectives

The main objectives of this project are to:

- Understand and clean the Student Performance Dataset
- Perform exploratory data analysis
- Calculate important statistical measures
- Apply probability and conditional probability
- Analyze relationships between variables using correlation
- Perform hypothesis testing
- Create meaningful data visualizations
- Apply Linear Algebra concepts to student data
- Apply Calculus concepts used in Machine Learning
- Demonstrate Gradient Descent
- Connect mathematical concepts with Machine Learning

---

📊 Topics Covered

Data Analysis

- Data loading
- Dataset understanding
- Data types and structure
- Missing value checking
- Duplicate checking
- Descriptive statistics
- Data visualization

Statistics

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Minimum
- Maximum
- Range

Probability

- Basic probability
- Conditional probability

Correlation

- G1 vs G3
- G2 vs G3
- Failures vs G3
- Correlation matrix
- Correlation heatmap

Hypothesis Testing

An independent two-sample t-test is performed to compare the average final grades of male and female students.

- Null Hypothesis (H0)
- Alternative Hypothesis (H1)
- Significance level α = 0.05
- T-statistic
- P-value
- Statistical conclusion

Linear Algebra

The project demonstrates:

- Vectors
- Vector addition
- Matrices
- Matrix transpose
- Dot product
- Matrix multiplication
- Weighted performance scores

Calculus

The project covers:

- Derivatives
- Partial derivatives
- Gradients
- Gradient Descent
- Cost Function
- Mean Squared Error (MSE)

---

📈 Visualizations

The project contains multiple visualizations to understand student performance:

1. Distribution of Final Grades
2. Gender Count
3. Average Final Grade by Gender
4. Study Time vs Average Final Grade
5. Past Failures vs Final Grade
6. G2 vs Final Grade
7. G1 vs Final Grade
8. Absences vs Final Grade
9. Correlation Heatmap

Each visualization includes a short interpretation of the observed pattern.

---

🔬 Statistical Findings

Some important findings from the analysis include:

- Mean final grade: ≈ 10.42
- Median final grade: 11
- Mode final grade: 10
- Standard deviation: ≈ 4.58
- Grade range: 20
- Probability of "G3 ≥ 10": ≈ 67.09%

---

🔗 Correlation Findings

The analysis shows:

- G2 and G3: ≈ 0.905
- G1 and G3: ≈ 0.801
- Failures and G3: ≈ -0.360

This indicates that previous grades, especially G2, have a strong positive relationship with final performance, while previous failures have a negative relationship with final grades.

---

🧪 Hypothesis Testing Result

An independent two-sample t-test was performed to compare the final grades of male and female students.

Hypotheses

H0: There is no significant difference between the mean final grades of male and female students.

H1: There is a significant difference between the mean final grades of male and female students.

Result

- Male mean G3: ≈ 10.914
- Female mean G3: ≈ 9.966
- T-statistic: ≈ 2.065
- P-value: ≈ 0.0396
- Significance level: 0.05

Since the p-value is below 0.05, the null hypothesis is rejected for this sample.

This result indicates a statistically significant difference between the two group means in this dataset. It does not establish that gender causes the difference.

---

🧮 Linear Algebra Application

Student performance data is represented using vectors and matrices.

For example:

[G1, G2, G3]

The project demonstrates how:

- Vectors represent student features
- Matrices represent multiple students
- Transpose changes rows into columns
- Dot products calculate weighted scores
- Matrix multiplication performs calculations using features and weights

This demonstrates the basic mathematical operations used in Machine Learning.

---

📐 Calculus & Gradient Descent

The project demonstrates how calculus is connected to Machine Learning.

Derivative

For:

y = x²

The derivative is:

dy/dx = 2x

Partial Derivatives

For:

f(x,y) = x² + y²

The partial derivatives are:

∂f/∂x = 2x
∂f/∂y = 2y

Gradient

At "(3,4)":

Gradient = [6,8]

Gradient Descent

Gradient Descent is demonstrated using:

new value = old value - learning rate × gradient

A simple student-performance model is also implemented using G1, G2, and Failures to estimate G3.

The model updates its weights using gradients to reduce the prediction error.

---

🧠 Key Observations

1. Previous grades are strongly related to final performance.
2. G2 has the strongest positive relationship with G3.
3. G1 also has a strong positive relationship with G3.
4. More previous failures are associated with lower final grades.
5. Approximately 67.09% of students achieved a final grade of 10 or higher.
6. Statistical hypothesis testing was applied to compare group means.
7. Student data can be represented using vectors and matrices.
8. Dot products and matrix multiplication can be used for weighted calculations.
9. Derivatives and gradients demonstrate the mathematical foundation of optimization.
10. Gradient Descent shows how an ML model can reduce prediction error step by step.

---

🛠️ Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- SymPy
- Jupyter Notebook

---

📁 Project Structure

Student-Performance-Analysis/
│
├── Student_Performance_Analysis.ipynb
├── student_data.csv
├── README.md
└── requirements.txt

---

👩‍💻 Author

Romaisa Atiq

BS Artificial Intelligence Student
The Islamia University of Bahawalpur

Areas of Interest

- Machine Learning
- Data Analysis
- Python
- Artificial Intelligence
- Data Visualization
- Mathematical Foundations of Machine Learning

---

📚 Project Purpose

This project was developed as an academic and practical exercise to understand how Python, Statistics, Probability, Linear Algebra, and Calculus can be applied to real-world student performance data.

It also demonstrates how mathematical concepts form an important foundation for Machine Learning.

---

⭐ Conclusion

The project demonstrates a complete analytical workflow, starting from data loading and cleaning and moving toward statistical analysis, visualization, hypothesis testing, Linear Algebra, Calculus, and Gradient Descent.

Overall, it shows how Python + Statistics + Probability + Linear Algebra + Calculus work together as important foundations for Machine Learning.
