### Graduate-Admissions-Analysis
In this project, I performed an analysis of graduate admissions using exploratory data analysis (EDA) and linear regression techniques. The goal was to understand the factors influencing graduate admissions and develop a predictive model for admission chances.

### Data
I started by importing the dataset and conducting typical EDA steps to examine its structure and characteristics. I ensured that the dataset did not contain any unique row identifiers, as I wanted to avoid building any understanding based on row numbers.

### Exploratory Data Analysis
I used both non-graphical and graphical analysis techniques to gain insights into the variables related to graduate admissions. I examined the distribution of variables to ensure a diverse range of student merit in the dataset.

### Variable Relationships
I explored the relationships between different factors that play a role in graduate admissions. Specifically, I investigated the correlation among independent variables and their interactions with each other. This analysis helped me understand the interdependencies and potential predictors of admission chances.

### Linear Regression
I employed linear regression using the Statsmodels library to build a predictive model for graduate admissions. The linear regression model allowed me to examine the relationships between the independent variables and the dependent variable (admission chances). I analyzed the results of the regression model to gain insights into the factors influencing admissions.

### Assumptions of Linear Regression
I tested several assumptions of linear regression to ensure the validity of the model. These included:

**Multicollinearity check by VIF score:** I examined the variance inflation factor (VIF) to assess multicollinearity among the independent variables.

**Mean of residuals:** I analyzed the mean of the residuals to evaluate the model's bias.

**Linearity of variables:** I examined the residual plot for any patterns, ensuring a linear relationship between the independent variables and the dependent variable.

**Homoscedasticity test:** I tested for homoscedasticity to verify that the residuals had constant variance.

**Normality of residuals:** I assessed the normality of the residuals to ensure they followed a normal distribution.

### Model Evaluation
I evaluated the performance of the linear regression model using various metrics, including mean absolute error (MAE), root mean squared error (RMSE), R-squared score (R2), and adjusted R-squared score. These metrics provided an indication of how well the model fit the data and predicted admission chances.

### Insights and Recommendations
Based on the analysis, I gained actionable insights into the factors influencing graduate admissions. These insights can be used by the Education Institute to enhance their understanding of the admissions process and make informed decisions. Additionally, I provided recommendations on potential strategies to improve admission chances for prospective students.
