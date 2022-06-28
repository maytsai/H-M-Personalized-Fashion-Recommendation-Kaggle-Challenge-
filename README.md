# H&M-Personalized-Fashion-Recommendation-Kaggle-Challenge

## Project Description
The project was given purchase history of customers across time, along with supporting metadata from H&M. Our challenge is to support the dats exploratory on H&M's Marketing Strategy on Email Marketing and buying preference on the articles. Moreover, build a fashion recommendation model to sustain the increased sales from their online channel post COVID19 pandemic.

## Datasets
- articles.csv: detailed metadata for each article_id available for purchase
- customers.csv -metadata for each customer_id in dataset
- transactions_train.csv - the training data, consisting of the purchases each customer for each date, as well as additional information. Duplicate rows correspond to multiple purchases of the same item. Your task is to predict the article_ids each customer will purchase during the 7-day period immediately after the training data period.

## Exploratory Data Analytics
To have a better understanding on the company products, customers, and transaction, we want to answer following questions.

**Product Analysis**
- Which category of clothing is the most sold by H&M?

**Customer Analysis**
- Which age group purchases more products?
- Which age group generates more earnings for the company?
- Do active customers on the fashion news purchase more articles?

**Transactional Analysis**
- Which are the top 50 popular products in terms of their sold quantity?
- Which are the top 50 products that generated most earnings for the company?
- What product category generated least earning for the company?

## Methodology
**Kmeans Clustering**
To build the personalized recommendation model, the first step we take is to utilize unsupervised learning method k-means to cluster articles dataset. By knowing th optimal K and cluster into 4 groups, we have prepared to run the the predictive analytics on customers datasets merging with the cluster groups.

**Predictive analysis**
We implemented 6 classification models to our data and found out that Decision Tree yielded the best accuracy out of every other model. It outperforms KNN, Gradient Boosting Classifier, Random Forest, Gaussian Naive Bayes, and Linear SVC.

## Conclusion
After running all the algorithms, we would recommend that H&M uses Decision Tree model to recommend a more personalized collection to its customers and enhance the online shopping experience.

## Reference
1. H&M. (2022, February 7). H&M personalized fashion recommendations. Kaggle. Retrieved May 3, 2022, from https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations

2. Python PCA tutorial: Principal component analysis with Sklearn. DataCamp Community. (n.d.).Retrieved May 3, 2022, from https://www.datacamp.com/community/tutorials/principal-component-analysis-in-python

3. Data Science in retail industry: Data Science Use Cases in retail industry. Analytics Vidhya. (2021, May 11). Retrieved May 3, 2022,from https://www.analyticsvidhya.com/blog/2021/05/data-science-use-cases-in-retail-industry/

4. KNN classification tutorial using Sklearn Python. DataCamp Community. (n.d.). Retrieved May 3, 2022, from https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn



