Scarlett Scott
sfscott@ucsd.edu
D04 - Biwei Huang

**What is the most interesting topic covered in your domain this quarter?**
The topic I find most interesting is how data cleaning affects the ability of forecasting agents to learn
from historical data. My DSC180A project involves data cleaning and forecasting, and I am interested in how 
decisions about missing values, inconsistent records, and unusual observations influence predictions. I 
would like to understand how to prepare reliable training data while preserving the information needed to 
forecast future outcomes.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
For my Quarter 2 Project, I would like to investigate how different data-cleaning strategies affect forecasting 
accuracy on previously unseen time periods. Using the historical dataset from our current project, I would compare 
a small number of approaches to handling missing values and outliers while keeping the forecasting agent and training 
settings consistent. I would train on earlier observations and evaluate predictions on later observations, comparing 
performance with a simple baseline that predicts the most recently observed value. I would measure accuracy using mean 
absolute error and examine whether the results are consistent across different time periods. The final result would be a 
pipeline explaining which cleaning choices helped, which did not, and their tradeoffs.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
One change I would make is to evaluate our data-cleaning decisions more systematically. I would compare several versions 
of the preprocessing pipeline, changing one component at a time to understand its effect on forecasting performance. I would 
also check that every prediction uses only information available at the time it would have been made. Any preprocessing steps 
that learn from data would be fitted only on the training period. This would help distinguish improvements that hold up on 
future observations from results that depend on a particular evaluation period or accidental access to future information.

**What other techniques would you be interested in using in your project?**
I would be interested in exploring lagged features and rolling summaries to help forecasting agents capture recent patterns in 
historical data. I would also like to use walk-forward evaluation, where the training period moves forward and the system repeatedly 
predicts the next period which would let me examine how performance changes over time. I would explore prediction intervals to communicate 
uncertainty along with each forecast. 
