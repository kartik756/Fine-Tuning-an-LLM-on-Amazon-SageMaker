Fine-Tuning an LLM on Amazon SageMaker

📌 Project Overview
This project demonstrates fine-tuning a pre-trained Large Language Model (LLM) using Amazon SageMaker for a domain-specific enterprise FAQ assistant.
The goal was to adapt a foundation model to answer internal knowledge-base questions more accurately by training it on curated domain-specific datasets and deploying it as a scalable API endpoint.
This project was implemented using AWS SimuLearn lab environment.

🎯 Objective
Fine-tune a pre-trained LLM on domain-specific FAQ data
Optimize model performance for accuracy and response relevance
Deploy the fine-tuned model to a SageMaker endpoint
Integrate the endpoint with a serverless API architecture
Enable real-time inference via API Gateway + Lambda

⚙️ Fine-Tuning Strategy
Loaded pre-trained foundation model
Used supervised fine-tuning approach
Configured:
Learning rate
Batch size
Epoch count
Monitored training metrics:
Loss
Validation loss
Optimization techniques:
Reduced overfitting using validation split
Adjusted learning rate scheduler
Used early stopping criteria

🚀 Deployment
After training:
Model artifacts stored in S3
Created SageMaker model object
Configured endpoint configuration
Deployed real-time inference endpoint
Tested endpoint using boto3 invoke_endpoint API

📈 Results
Improved domain response relevance compared to base model
Reduced hallucination in enterprise-specific queries
Achieved lower validation loss after fine-tuning
Enabled production-ready deployment via scalable endpoint

My architecture:
<img width="1440" height="860" alt="Fine-Tuning-an-LLM-on-Amazon-SageMaker" src="https://github.com/user-attachments/assets/caf12fb7-f1b5-4e03-aa85-6d692e643346" />

Proof of completion:
<img width="1152" height="896" alt="FIne-tuning-LLM-kartik_Patil" src="https://github.com/user-attachments/assets/9c552675-3b47-4052-a105-862963c4647a" />

