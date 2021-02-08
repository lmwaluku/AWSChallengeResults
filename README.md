# AWS Challenge Results

## SECTION A
#### Architecture Diagram for Data Ingestion from On-premise to the AWS Cloud

## SECTION B
#### Firewall will give access to the backend via the gateway to the VPC. The gateway will route traffic to the S3 storage. 

#### AWS Step Function in collaboration with AWS Lambda will trigger ingestion that will allow data to be transformed or enriched then send to AWS Dynamo for storage. 

#### Amazon Glue will clean, validate and transform data for storage to data warehouse and or for data analytical

#### Glue Data Catalog will be used for data indexing and to ensure created ETL are monitored and managed accordingly before being send to Amazon Athena.

#### Amazon Athena then queries all the data in the S3 using standard SQL.

