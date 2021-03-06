# Document History for AWS Glue<a name="doc-history"></a>

The following table describes important changes to the documentation for AWS Glue\.
+ **Latest API version:** 2018\-10\-15
+ **Latest documentation update:** October 15, 2018

| Change | Description | Date | 
| --- |--- |--- |
| [Support for resource\-level permission and resource\-based policies](#doc-history) | Added information about using resource\-level permissions and resource\-based policies with AWS Glue\. For more information, see the topics within [Security in AWS Glue](https://docs.aws.amazon.com/glue/latest/dg/security-glue.html)\. | October 15, 2018 | 
| [Support for Amazon SageMaker notebooks](#doc-history) | Added information about using Amazon SageMaker notebooks with AWS Glue development endpoints\. For more information, see [ Managing Notebooks](https://docs.aws.amazon.com/glue/latest/dg/notebooks-with-glue.html)\. | October 5, 2018 | 
| [Support for encryption](#doc-history) | Added information about using encryption with AWS Glue\. For more information, see [ Encryption and Secure Access for AWS Glue](https://docs.aws.amazon.com/glue/latest/dg/encryption-glue-resources.html) and [Setting Up Encryption in AWS Glue](https://docs.aws.amazon.com/glue/latest/dg/set-up-encryption.html)\. | August 24, 2018 | 
| [Support for Apache Spark job metrics](#doc-history) | Added information about the use of Apache Spark metrics for better debugging and profiling of ETL jobs\. You can easily track runtime metrics such as bytes read and written, memory usage and CPU load of the driver and executors, and data shuffles among executors from the AWS Glue console\. For more information, see [ Monitoring AWS Glue Using CloudWatch Metrics](https://docs.aws.amazon.com/glue/latest/dg/monitoring-awsglue-with-cloudwatch-metrics.html), [Job Monitoring and Debugging](https://docs.aws.amazon.com/glue/latest/dg/monitor-profile-glue-job-cloudwatch-metrics.html) and [Working with Jobs on the AWS Glue Console](https://docs.aws.amazon.com/glue/latest/dg/console-jobs.html)\. | July 13, 2018 | 
| [Support of DynamoDB as a data source](#doc-history) | Added information about crawling DynamoDB and using it as a data source of ETL jobs\. For more information, see [Cataloging Tables with a Crawler](https://docs.aws.amazon.com/glue/latest/dg/add-crawler.html) and [Connection Parameters](https://docs.aws.amazon.com/glue/latest/dg/aws-glue-programming-etl-connect.html)\. | July 10, 2018 | 
| [Updates to create notebook server procedure](#doc-history) | Updated information about how to create a notebook server on an Amazon EC2 instance associated with a development endpoint\. For more information, see [Creating a Notebook Server Associated with a Development Endpoint](https://docs.aws.amazon.com/glue/latest/dg/dev-endpoint-notebook-server-considerations.html)\. | July 9, 2018 | 
| [Updates now available over RSS](#doc-history) | You can now subscribe to an RSS feed to receive notifications about updates to the AWS Glue Developer Guide\. | June 25, 2018 | 
| [Support delay notifications for jobs](#doc-history) | Added information about configuring a delay threshold when a job runs\. For more information, see [Adding Jobs in AWS Glue](https://docs.aws.amazon.com/glue/latest/dg/add-job.html)\. | May 25, 2018 | 
| [Configure a crawler to append new columns](#doc-history) | Added information about new configuration option for crawlers, MergeNewColumns\. For more information, see [Configuring a Crawler](https://docs.aws.amazon.com/glue/latest/dg/crawler-configuration.html)\. | May 7, 2018 | 
| [Support timeout of jobs](#doc-history) | Added information about setting a timeout threshold when a job runs\. For more information, see [Adding Jobs in AWS Glue](https://docs.aws.amazon.com/glue/latest/dg/add-job.html)\. | April 10, 2018 | 
| [Support Scala ETL script and trigger jobs based on additional run states](#doc-history) | Added information about using Scala as the ETL programming language\. In addition, the trigger API now supports firing when any conditions are met \(in addition to all conditions\)\. Also, jobs can be triggered based on a "failed" or "stopped" job run \(in addition to a "succeeded" job run\)\. | January 12, 2018 | 

## Earlier Updates<a name="WhatsNew.earlier-updates"></a>

The following table describes the important changes in each release of the *AWS Glue Developer Guide* before January 2018\.


****  

| Change | Description | Date | 
| --- | --- | --- | 
| Support XML data sources and new crawler configuration option | Added information about classifying XML data sources and new crawler option for partition changes\.  | November 16, 2017 | 
| New transforms, support for additional Amazon RDS database engines, and development endpoint enhancements | Added information about the map and filter transforms, support for Amazon RDS Microsoft SQL Server and Amazon RDS Oracle, and new features for development endpoints\. | September 29, 2017 | 
| AWS Glue initial release | This is the initial release of the AWS Glue Developer Guide\. | August 14, 2017 | 