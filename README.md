# portfolio_projects

Welcome to my portfolio projects repository! Here you will find a collection of projects showcasing my skills in data science and web development. Each project demonstrates my ability to analyze data, create visualizations, and build web applications.

## Projects

### 1. Investigating Netflix Movies
**Description:** In this project, I performed exploratory data analysis (EDA) on a dataset of Netflix movies from the 1990s. The goal was to understand the distribution of movie durations and identify short action movies.

**Key Steps:**
1. **Data Exploration:**
   - Familiarized myself with the dataset by checking data types and identifying missing values (none found).
   - Obtained an overview of the dataset, including basic statistics and structure.
   
2. **Data Cleaning:**
   - Ensured the dataset was free of inconsistencies and duplicates.
   - Standardized the format of movie durations and genres for consistency.
   
3. **Analysis:**
   - Utilized Pandas for data manipulation and analysis.
   - Calculated the distribution of movie durations and identified patterns.
   - Filtered and categorized movies based on duration and genre.

**Results:**
- **Most Frequent Movie Duration (1990s):** The most frequent duration was calculated to be approximately 94 minutes.
- **Count of Short Action Movies (Less than 90 minutes):** Identified and counted 7 short action movies from the 1990s.

**Learning Outcomes:**
- Gained experience in data cleaning and exploratory data analysis.
- Developed skills in using Pandas for data manipulation and analysis.
- Applied best coding practices in Python for data analysis.



### 2. Exploring NYC Public School Test Result Scores
**Description:** This project explores test result scores of NYC public schools, identifying schools with the best math results, top-performing schools based on combined SAT scores, and the borough with the largest standard deviation in combined SAT scores.

**Key Steps:**
1. **Identifying Schools with Best Math Results:** 
   - Filtered schools with an average math score of at least 80% of the maximum possible score (800).
   - Saved results in a DataFrame called `best_math_schools`, including "school_name" and "average_math" columns.
   
2. **Determining Top 10 Performing Schools Based on Combined SAT Scores:** 
   - Calculated the total SAT score by summing the individual SAT section scores.
   - Sorted the schools by the combined SAT scores.
   - Saved results in a DataFrame called `top_10_schools`, including "school_name" and a new column "total_SAT".
   
3. **Finding the Borough with the Largest Standard Deviation in Combined SAT Scores:** 
   - Calculated the standard deviation of the combined SAT scores for each borough.
   - Identified the borough with the largest standard deviation.
   - Saved results in a DataFrame called `largest_std_dev`, including "borough", "num_schools", "average_SAT", and "std_SAT".

**Results:**
- **Best Math Results:** Identified schools with an average math score of at least 640 (80% of 800). Results saved in `best_math_schools` DataFrame.
- **Top 10 Performing Schools:** Listed top 10 schools based on combined SAT scores. Results saved in `top_10_schools` DataFrame.
- **Largest Standard Deviation in Combined SAT Scores:** Determined the borough with the largest standard deviation of combined SAT scores. Results saved in `largest_std_dev` DataFrame.

**Learning Outcomes:**
- Enhanced skills in data manipulation and analysis using Pandas, including filtering, sorting, and grouping data.
- Gained insights into visualizing and interpreting real-world educational data to identify trends and patterns.



# Project Upload Format
### 2. [New Project Title]
**Description:** Brief overview of the new project.

**Key Steps:**
1. **Step 1:** Description of the step.
2. **Step 2:** Description of the step.
3. **Step 3:** Description of the step.

**Results:**
- **Key Result 1:** Summary of result.
- **Key Result 2:** Summary of result.

**Learning Outcomes:**
- Learning 1
- Learning 2

## Getting Started

To get started with this repository, clone it using the following command:

```bash
git clone https://github.com/yourusername/portfolio_projects.git
