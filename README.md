# AWS Sagemaker ML Model Integration Lambda and API Gateway 

### Build & Deploy SciKit Learn Machine Learning Model with AWS Sagemaker and Integrate it to Lambda, API Gateway

#### Amazon SageMaker is a fully-managed platform that enables developers and data scientists to quickly and easily build, train, and deploy machine learning (ML) models at any scale.

#### AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume.

#### Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. APIs act as the "front door" for applications to access data, business logic, or functionality from your backend services.

## Project UseCase :

#### Maersk is a Danish shipping company, active in ocean and inland freight transportation and associated services, such as supply chain management and port operation. Maersk has invested in different business segments like FMCG, Fashion & lifestyle, Retail, Chemicals, Automotive, Technology & Electronics, Pharma and Healthcare, Logistics etc. But Maersk wants to minimise their spending in these segments and invest mostly in two main business segments, i.e., transport and logistics and energy.

We will be predicting the profit from different segments mentioned above. We’re using the Maersk dataset for this problem statement, and we will be using the concept of regression to predict the profit for spending in different segments.

#### Dataset link : maresk.csv

#### Procedure Followed :-> 
- Sagemaker Training and Model Deployment
- AWS Lambda for Model Prediction
- AWS API Gateway for model services

### Sagemaker Training and Model Deployment

##### Creating a Notebook instance, giving IAM role, Loading Datasets, Training, Deploying and Creating MOdel Endpoint
![img_2.png](images%2Fimg_2.png)

![img.png](images%2Fimg.png)

![img_1.png](images%2Fimg_1.png)

### AWS Lambda

##### We have deployed model and deployed endpoint. So using this endpoint we will make prediction using AWS Lambda

![img_3.png](images%2Fimg_3.png)

![img_4.png](images%2Fimg_4.png)

### AWS API Gateway for model services 

##### Integration of Lambda function using API Gateway

![img_5.png](images%2Fimg_5.png)

![img_6.png](images%2Fimg_6.png)

![img_7.png](images%2Fimg_7.png)

![img_8.png](images%2Fimg_8.png)

![img_9.png](images%2Fimg_9.png)

for API Testing we I have used free website

![img_10.png](images%2Fimg_10.png)







