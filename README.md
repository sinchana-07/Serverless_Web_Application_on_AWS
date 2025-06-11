# Serverless Web Application on AWS

## Description
This project has a serverless web application built using AWS Lambda, DynamoDB, and S3. The application will allow users to create, read, update, and delete (CRUD) items from a DynamoDB table.

## Architecture 
![image alt](https://github.com/sinchana-07/Serverless_Web_Application_on_AWS/blob/9944405730aca821425c0f706cef1e5f2677d9fc/aws%20proj%20img.png
)


## Steps to Build the Project:
Create a DynamoDB table to store the items.\
Build a Lambda function to handle the CRUD operations on the DynamoDB table.\
Use S3 to store and host the web application's static files (HTML, CSS, and JavaScript).\
Create a CloudFront distribution to serve the S3-hosted static files with low latency.\
