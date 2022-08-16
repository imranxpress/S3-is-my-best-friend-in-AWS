# S3 is my best friend in AWS:
![awss3](https://user-images.githubusercontent.com/47071968/184665878-5b7874ce-c486-4bbf-b44f-a200d97bd053.jpg)

Amazon Simple Storage Service which is known as S3 bucket, the most adorable services from AWS. S3 bucket stores data as an object within AWS. Any files, folders of files and file metadata can be stored in S3 in such an efficient way that behaves like it has virtually unlimited storage capability to store your data. Isn't it fascinating! 


> ### Get Industry-leading scalability, Best data availability, Top most security and Unparalleled performance from Amazon S3.

Amazon S3 is designed for 99.999999999% (11 9's) of durability, and stores data for millions of applications for companies all around the world. Have a look on the intro to S3:

## :point_right: https://youtu.be/_I14_sXHO8U 

Top of all these, S3 has some cool and hot features that can be configured so easily without any cloud experience required. Some key features are like:

1. S3 is a global AWS service but you can define any S3 bucket to be available for any specific region while creating it and can't change after that.

2. S3 has an awesome feature to host static websites faster than ever.

3. Versioning enabled and MFA delete activated S3 buckets can stop accidental deletion of objects from bucket.

4. S3 has 6 different types of storage classes for different use-cases.

5. A total of 5 GB of data can be uploaded at a time but more than that size of object requires another feature to use to upload called "Multipart upload API".

6. S3 stored object can have "Life Cycle Policy" to handle data usage over specific time period and move data from one storage class to another automatically to save cost and storage.

7. Networking with S3 bucket object is so cool that you can easily configure it with existing system application in no time. Your user can access S3 hosted data with "Hosted style access", "Path style access", "Customized URL access", "Limited Usages access". Another best way to transfer data from on-premises data center to AWS Cloud is to use "S3 Transfer Acceleration" and make it secure and faster.

![awss5](https://user-images.githubusercontent.com/47071968/184670127-e98c5084-a597-4dcf-b3a2-d9c3bed9b3a7.png)


8. Distribute your content to end user in a fastest way by using AWS CloudFront attached to S3 to serve data from AWS Edge locations.

9. Security is the top most priority in AWS and with S3 you can do so by a lot's of ways. S3 provides "Bucket Policy" to handle and define security of the object in any S3 bucket or any specific bucket as a whole. There are 4 parts in a bucket policy to keep in mind to write the JSON policy. "Resources", "Actions", "Effects", "Principals" are the key parts of any S3 bucket policy to define security and handle access for the end users. 

10. Encryption and Monitoring are two cool features of S3 which you will have to configure by yourself. Server Side Encryption with "KMS provided and managed : SSE-KMS", "S3 provided and managed : SSE-S3", "Customer provided and managed : SSE-C" and Client Side Encryption with "KMS managed customer Master Key" & "Customer Managed Master Key" are the available ways to encrypt S3 bucket objects on cloud.

Monitoring in S3 comes with some extra-cool features like "Automated monitoring CloudWatch" to set alarms and generate metrics to get clear picture of what is happening within your bucket and "Automated monitoring CloudTrail" to log monitoring and share insightful real time analytics out of them. Even you can create your own custom metrics for your buckets based on these two services to get most out of it.

### Few most advanced feature and Use-cases for S3:

1. [Requester Pays Buckets ](https://docs.aws.amazon.com/AmazonS3/latest/userguide/RequesterPaysBuckets.html): Learn how to configure a bucket so that a customer pays for the downloads they make.

2.  [Using BitTorrent With Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/uploading-downloading-objects.html): Use BitTorrent, which is an open, peer-to-peer protocol for distributing files.

3.  [Build Data Lakes](https://aws.amazon.com/products/storage/data-lake-storage/) : With a data lake built on Amazon S3, you can use native AWS services to run big data analytics, artificial intelligence (AI), machine learning (ML), high-performance computing (HPC) and media data processing applications to gain insights from your unstructured data sets.

4.  [S3 as Serverless Storage](https://aws.amazon.com/blogs/compute/building-scalable-serverless-applications-with-amazon-s3-and-aws-lambda/) : Consider S3 as the Serverless Storage and add S3 as much as you can in your Serverless Solution Architecture.

### I feel like S3 is my ultimate friend in all the AWS services out there. I love Serverless solutions and try my best to incorporate S3 there. Have a look on how the S3-to-Lambda pattern can implement the following business solutions:


![awss36](https://user-images.githubusercontent.com/47071968/184672352-77565d98-1ad6-45bc-ab59-bfa0814aec3e.png)


1.  [Translating documents at scale](https://aws.amazon.com/blogs/compute/translating-documents-at-enterprise-scale-with-serverless/), by using  [Amazon Translate](https://aws.amazon.com/translate/) in response to S3 events.

2.  [Automating data imports to DynamoDB](https://aws.amazon.com/blogs/compute/creating-a-scalable-serverless-import-process-for-amazon-dynamodb/) tables using objects stored in an S3 bucket.

3. [Creating a searchable enterprise document repository](https://aws.amazon.com/blogs/compute/creating-a-searchable-enterprise-document-repository/), using S3 and [Amazon ML services](https://aws.amazon.com/machine-learning/).

4. [ Automating scalable business workflows](https://aws.amazon.com/blogs/compute/automating-scalable-business-workflows-using-minimal-code/), integrating S3 and [AWS Step Functions ](https://aws.amazon.com/step-functions/?step-functions.sort-by=item.additionalFields.postDateTime&step-functions.sort-order=desc).

5.  [Converting call center recordings](https://aws.amazon.com/blogs/compute/converting-call-center-recordings-into-useful-data-for-analytics/) into useful data for analytics, using S3 with  [Amazon Transcribe](https://aws.amazon.com/transcribe/).


![awss7](https://user-images.githubusercontent.com/47071968/184672672-302f244f-a357-4090-b172-4bc3ab13aae2.jpg)


### Ok so this is the 3rd article of this #Serverless #series where I will highlight the most used Serverless Services form AWS. This is also a preparatory article for the upcoming certification exam!  Please keep me in your prayer.


