## Starting the project

### 1. Understanding the Data

Variable Names: 

- job_id: Unique identifier
- job_title: Role title
- industry: Industry category
- location: City of posting
- salary_usd: Annual salary in USD
- skills_required: Key skills
- remote_option: Yes/No
- company_size: Small/Medium/Large


### 2. Libraries / Dependencies

You will use `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn` libraries. If you haven't already, please install these libraries using pip/pip3 or conda install.


### Exploratory Data Analysis (EDA)

## Part 1: 

1. Import libraries:
``` python    
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
- pandas: For data manipulation and analysis
- seaborn: For statistical data visualization
- matplotlib.pyplot: For creating plots and charts
  
2. Assign 'df', a standard variable for DataFrame, using the `read_csv` function from the `pandas` library.
   
- Ensure the DataFrame and dataset work by running `shape.` Output needs to be (10000, 9)

3. Analyze the first 5 rows of the dataset with `head()` and `info().`

4. Create a list that sorts `skills_required` by their frequency. Then print the top 10 skills and the amount of time the skill appears.

5. By using the seaborn and matplotlib libraries, graph the top 10 skills.

6. Summarize your findings from steps 3-5 in 3-4 sentences.

## Part 2: 

1. Similar to part 1, step 5, sort the top skills for each job title.
   
   * **Hint 1:** Use `groupby` on job_title
     
2. Find the average salary of each job

3. Compare the total amount of remote and non-remote. Moreover, find the percentage of AI/Machine learning jobs for each remote and non-remote.

4. Find the probability of jobs in each city belonging to each industry.

## Part 3:

1. Graph AI jobs by City and Industry with a heatmap.
   
   * href= https://seaborn.pydata.org/generated/seaborn.heatmap.html
   
2. Use the `numpy` library to find the mean, median, max, and min of the salaries.

3a. import KMeans from sklearn.cluster. The goal is to generate 3 clusters to predict which will result in a higher salary.

3b. Output the min, mean, and max of the 3 groups. 

  * https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html


