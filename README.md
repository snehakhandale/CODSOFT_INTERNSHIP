# Titanic-Survival-Analysis
Analysis of Titanic survival data using Python and visualization libraries.

# Overview
This project is part of Task 1 of my CODSOFT Data Science internship. The objective of this analysis is to explore the Titanic dataset and uncover insights related to the survival of passengers based on various factors such as gender, class, and age.

# Dataset
The dataset used in this analysis is the famous Titanic dataset, which contains information on the passengers aboard the Titanic, including whether they survived or not. The dataset has the following columns:

- PassengerId: Unique identifier for each passenger
- Survived: Survival status (0 = No, 1 = Yes)
- Pclass: Passenger class (1 = First, 2 = Second, 3 = Third)
- Name: Passenger's name
- Sex: Passenger's gender
- Age: Passenger's age
- SibSp: Number of siblings/spouses aboard the Titanic
- Parch: Number of parents/children aboard the Titanic
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

# Analysis
1. Data Cleaning and Preparation
Handling Missing Values: Missing values in the 'Age' column were handled by imputing with the median age.
Data Transformation: Converted categorical columns like 'Sex' and 'Embarked' into numerical categories for easier analysis.

2. Exploratory Data Analysis (EDA)
Survival Rate by Gender: Analyzed the survival rate based on gender, finding that women had a higher survival rate than men.
Survival Rate by Class: Explored the survival rates across different passenger classes (Pclass), observing that first-class passengers had the highest survival rate.
Age Distribution: Examined the distribution of ages among passengers and analyzed survival rates across different age groups.

3. Visualizations
Gender Distribution: Created a pie chart to visualize the distribution of genders among passengers.
Survival Rate by Embarkation Location: Used a bar chart to show survival rates based on the port of embarkation.
Fare vs. Survival: Analyzed the relationship between the fare paid and survival, using scatter plots and box plots.

# Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Matplotlib: For creating static visualizations.
Seaborn: For advanced and aesthetically pleasing statistical visualizations.

# Conclusion
This analysis provided valuable insights into the factors that influenced survival on the Titanic. The findings could be useful for understanding passenger demographics and safety protocols. Further analysis could include more advanced techniques like machine learning models to predict survival based on the features in the dataset.

# How to Use
To run the analysis yourself:

1. Clone this repository: git clone https://github.com/your-username/titanic-survival-analysis.git
2. Install the required libraries: pip install -r requirements.txt
3. Run the Jupyter notebook titanic_survival_analysis.ipynb to see the analysis and visualizations.

# Acknowledgements
This project is based on the Titanic dataset from Kaggle. Special thanks to CODSOFT for the opportunity to explore and analyze this dataset as part of their data science internship program.
