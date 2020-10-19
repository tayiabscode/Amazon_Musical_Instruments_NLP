# Amazon Musical Instruments NLP
Due to advances in technnology over the last couple of decades we now live in a world where it has never been easier for consumers to purchase products. Consumers can now purchase everything from groceries to furniture from the comfort of their homes all with the click of a button.

One of the leaders of the e-commerce space is Amazon a multinational and multibillion dollar technology and e-commerce business. Amazon's marketplace has a plethora of products for customer to purchase and is said to sell over 12 million products in 2020 which does not include products sold by third parties on its marketplace.

With the abundance of products available to customers how do they know they are purchasing a high quality product that suits their needs? This problem is largely addressed by user reviews made by customers who have already purchased the advertised products allowing future customers to make more informed purchases. This particular dataset contains amazon reviews between the years 2004-2014 for various musical instruments sold on the website. 

## Purpose of Project
To predict whether a consumer had a positive or negative experience after purchasing a musical instrument from amazon based on the reviews they wrote for the product.

## Results
A variety of machine learning algorithms were used specifically Naive Bayes, Logistic Regression and Random Forests. After balancing the dataset with synthetic data using SMOTE the random forest classifier performed the best with a 98% accuracy. The final model was then tested with current reviews from amazon and classified each of these reviews correctly.

## Future Work and Improvements
The data is only for the years 2004-2014 so having a more complete dataset from the year the first review was wrote to the present would allow for a more complete analysis, adiitionally connecting the model to live data would streamline this process.
Additionally it would be interesting to supplement this dataset with sales data to see how the reviews on a product and the overall rating effects sales.

## Inspiration and credit
This analysis was based on the yelp reviews natural language portfolio project I completed as part of the course 'Introduction to Data Science with Python and Machine Learning Bootcamp' by Jose Portilla. I was inspired by my friend Ramon who took the portfolio project further, you can see his Yelp Reviews NLP project [here.](https://github.com/RamonJWS/Restaurant_Review_NLP)  <br><br>
Dataset taken from [kaggle.](https://www.kaggle.com/eswarchandt/amazon-music-reviews)
