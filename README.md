# Receipt-Scan-Project

Project Overview: Sustainability Score Calculation for Receipts

This project aims to provide a Sustainability Score for each receipt uploaded by users. Below is a detailed procedure outlining the workflow:

->Receipt Upload: Users upload a receipt in either image or PDF format.

->Storage: The uploaded receipt is stored in an AWS S3 bucket.

->Data Extraction: Using AWS Textract OCR, data from the receipt is extracted and stored in a DynamoDB database.

->Score Calculation: The extracted data is passed to the Gemini LLM, which calculates the sustainability score based on the items listed on the receipt.

->Score Storage: The calculated sustainability score is then stored back in the AWS DynamoDB table.


This systematic approach ensures accurate sustainability scoring based on the items purchased, leveraging AWS services for efficient data processing and storage.






