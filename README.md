# Logistic-Regression-Model-to-Determine-User-Clicks-on-Ads

## Project Overview:
Worked with a advertising data set, indicating whether or not a particular internet user clicked on an Advertisement on a company website. Created a model that will predict whether or not they will click on an ad based on the features of that user.

## Dataset:
This data set contains the following features:
<ul>
  <li>'Daily Time Spent on Site': consumer time on site in minutes</li>
  <li>'Age': cutomer age in years</li>
  <li>'Area Income': Avg. Income of geographical area of consumer</li>
  <li>'Daily Internet Usage': Avg. minutes a day consumer is on the internet</li>
  <li>'Ad Topic Line': Headline of the advertisement</li>
  <li>'City': City of consumer</li>
  <li>'Male': Whether or not consumer was male</li>
  <li>'Country': Country of consumer</li>
  <li>'Timestamp': Time at which consumer clicked on Ad or closed window</li>
  <li>'Clicked on Ad': 0 or 1 indicated clicking on Ad</li>
  </ul>
  
## Libraries Used:

<ul>
  <li>pandas</li>
  <li>numpy</li>
  <li>matplotlib</li>
  <li>seaborn </li>
  </ul>
 
 ## Exploratory Data Analysis:
 <p>Let's use seaborn to explore the data!</p>
 <h3>Create a histogram of the Age</h3>
 <img src="https://github.com/shahrukh-ak/Logistic-Regression-Model-to-Determine-User-Clicks-on-Ads/blob/main/Plots/1.png">
 
 <h3>Create a jointplot showing Area Income versus Age.</h3>
 <img src="https://github.com/shahrukh-ak/Logistic-Regression-Model-to-Determine-User-Clicks-on-Ads/blob/main/Plots/2.png">
 <h3>Create a jointplot showing the kde distributions of Daily Time spent on site vs. Age.</h3>
 <img src="https://github.com/shahrukh-ak/Logistic-Regression-Model-to-Determine-User-Clicks-on-Ads/blob/main/Plots/3.png">
 <h3>Create a jointplot of 'Daily Time Spent on Site' vs. 'Daily Internet Usage'</h3>
 <img src="https://github.com/shahrukh-ak/Logistic-Regression-Model-to-Determine-User-Clicks-on-Ads/blob/main/Plots/4.png">
 <h3>Finally, create a pairplot with the hue defined by the 'Clicked on Ad' column feature.</h3>
 <img src="https://github.com/shahrukh-ak/Logistic-Regression-Model-to-Determine-User-Clicks-on-Ads/blob/main/Plots/5.png">
 
 ## Model Training:
 
 <p>Next step I did is to split the data into training set and testing set using train_test_split and then train and fit a logistic regression model on the training set.</p>
 
## Predictions and Evaluations:
<p>Then I predict values for the testing data and created classification report for the model.</p>

![Results](https://user-images.githubusercontent.com/55116845/122092459-62b2e300-ce23-11eb-80bf-343c98fc7888.PNG)

## Results:
<p>Our model predicted the results with an accuracy and F1 score of 91%.</p>



 
 


  










