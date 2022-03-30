![image](https://raw.githubusercontent.com/Sirius0531/final_project/main/Resources/Images/BannerMain.jpg)
# Data Scientist Salary Analysis with Machine Learning

**Topic:**
Predicting the average salary of jobs in the data industry based on different variables using a linear regression model. We wanted to see how factors such as company, location and
experience affect the expected salary.

**The reason the topic was selected**
We selected this topic because it was one that was of interest to
all of us including our classmates. As we graduate from this
course and enter the job market we have a frame of reference
when negotiating offers.

**Description of the source of data:** 

JACK OGOZALY. (November 2021). 
Kaggle: Salary and more-Data Scientist, Analyst, Engineer, 
Retrieved 3/16/2022 from https://www.kaggle.com/jackogozaly/data-science-and-stem-salaries.
This dataset includes are job title, salary, company, years of experience, gender, education level and location. During our analysis, we hoped this dataset would help us answer the question of how do different factors such as location, years of experience, gender, and company affect the anticipated salary?

Limitations to Dataset
- Accuracy of the data because it was self-reported by humans
- Data did not include job descriptions, and all jobs were the same title
- There were several imbalances in the dataset such as company size, location, years of experience
- Total Yearly Compensation means different things to different people when self reporting (are stock options included, benefit packages, etc)

**Questions the team hopes to answer with the data**
How  do different factors, such as location, years of experience, gender, company, affect the anticipated salary.

**Description of the data exploration phase of the project**
We are using python and pandas to clean the dataset, filtering on data industry specific jobs in the USA.
Upload the cleaned dataset to S3 buket on AWS.
![image](https://user-images.githubusercontent.com/92349969/160261413-f58f0815-c402-407f-8edc-00913896e6cb.png)


**Description of the analysis phase of the project**
Machine Learning Model Selection
Once the data was clean we did visualizations of the data to decide which models may lend itself better to the data 
- We initially decided upon a linear model because what we were trying to find was a correlation rather than a classification
- Once we tired to linear regression model we decided to explore and build upon it with the Random Forest Regressor
- To see if we could improve the model and employ skills learned in class we also tested with a Neural Network

**Data Cleaning and Analysis**
We will use Pandas to clean and filter the dataset.

**Database Storage**
We will be using AWS and connecting to PostgreSQl to store our data.

**Machine Learning**
SciKitLearn is the ML library. We are doing multiple Linear Regression Models utilizing different variables from our dataset. We are also testing adding the Random Forest Classifier to our model as well. We will also use the Stats Model Library to evaluate the accuracy of our model.

**Dashboard**
We will create an interactive dashboard where users can choose variable from a drop down and see visualizations created with plotly. We will also use tableau to create visualizations for our presentation.



**Result of analysis**

**Recommendation for future analysis**

**Anything the team would have done differently**
