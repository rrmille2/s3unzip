# s3unzip

If you have an existing zip file in S3, this code will download the zipfile into memory and unzip it to a destination S3 bucket without having to do any S3 file copies.

This is best run on an EC2 instance (or SageMaker Notebook) that has very fast access to S3.


