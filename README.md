# animalsfourlife

A project showcasing a serverless AWS architecture for an animal data website.  
It features a static website hosted on S3 with CloudFront CDN, API Gateway & Lambda functions for backend processing, and data storage & analytics with Amazon Aurora, S3, and Athena.

---

## Project Overview

This project demonstrates a full AWS serverless stack, including:

- Static website hosting via **Amazon S3** with **CloudFront** distribution  
- REST API using **API Gateway** backed by **AWS Lambda** functions  
- Data storage with **Amazon Aurora (RDS)** and **S3 buckets** for raw and processed data  
- Data analytics via **AWS Athena** querying S3 data  
- Infrastructure monitoring with **CloudWatch** and security via **IAM**

---

## Architecture Diagram

![Architecture Diagram](docs/architecture.png)

---

## Getting Started

### Prerequisites

- AWS Account with proper permissions  
- AWS CLI configured  
- Git installed  
- Node.js (if frontend build tools used)  

### Installation

Clone the repo:

```bash
git clone https://github.com/mleib1337/animalsfourlife.git
cd animalsfourlife
