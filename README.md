# Online Course Popularity & Rating Analysis (Shaguf Platform)

## Project Overview
This data science project focuses on analyzing online course data from the local platform "Shaguf". The goal is to perform market benchmarking against global platforms (Udemy and Coursera) and build machine learning regression models to predict student enrollment and course popularity based on various academic and commercial features.

**Supervised by:** Dr. Reem Alqifari

## Project Pipeline

### 1. Data Collection & Preprocessing
* Developed automated web scrapers using **Python (BeautifulSoup & Selenium)** to extract a primary dataset of ~1,000 courses from Shaguf.
* Handled missing values, normalized categorical text, and performed robust data cleaning on raw outputs.

### 2. Exploratory Data Analysis (EDA)
* Analyzed regional pricing structures and the direct impact of promotional discounts on total student enrollment.
* Evaluated instructor reputation scores and their correlation with overall course ratings.
* Conducted cross-platform benchmarking utilizing global secondary datasets (~4,500 courses) from Udemy and Coursera.

### 3. Machine Learning Modeling
* Trained and evaluated multiple regression algorithms including **Linear Regression, Decision Tree, and Random Forest Regressor**.
* Achieved an optimal **R² score of 0.4827** using the Random Forest Regressor, capturing non-linear behavior patterns in market pricing and enrollment data.

## Technologies Used
* **Languages:** Python (Pandas, NumPy, Scikit-Learn, BeautifulSoup, Selenium)
* **Tools:** Jupyter Notebook, Git

## Team Members
* Noura Bader Alotaibi
* Aisha Fahad Alonizy
* Sadeem Abdullah Naseef
* Raghad Eid Almutairi
* Remas Eid Almutairi
