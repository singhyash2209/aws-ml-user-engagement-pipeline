# AWS ML Engagement Predictor Pipeline

## Overview

This project was developed as an industry-focused capstone for **Slicpix / Interactivity.studio**.  
It demonstrates an **end-to-end AWS machine learning pipeline** for predicting user engagement with interactive web plugins—mirroring real-world analytics challenges in digital product companies.

Key AWS services used: **S3, SageMaker, Lambda, API Gateway**.

The pipeline covers:
- Secure data and model storage on S3
- Automated data preprocessing and model training in SageMaker
- Deployment of a serverless inference API via Lambda (with real AWS IAM/permissions setup)
- Documentation with step-by-step screenshots and presentation/report artifacts

## Project Structure

- `notebook/` — Jupyter notebook for data preprocessing, model training, evaluation
- `src/` — Lambda handler code for real-time model inference
- `images/` — AWS setup and result screenshots (step-by-step)
- `docs/` — Presentation, reports, and supporting documents
- `data/` — (Dataset not included; see `data/README.md` for instructions)

## How to Run

1. **Upload** your engagement data to S3 (see screenshots for bucket config).
2. **Launch** the provided notebook in SageMaker; run all cells for preprocessing, training, and saving the model.
3. **Deploy** the Lambda function (`src/lambda_handler.py`) for inference, with correct IAM permissions (reference screenshots).
4. *(Optional)* Set up API Gateway for public endpoint access.
5. **See** `images/` for AWS step-by-step guidance.

## Results

- Achieved high classification accuracy on engagement prediction (see notebook for metrics)
- Fully automated and cloud-native workflow, suitable for production-scale scenarios
- **Industry context:** Simulates real ML product development for Slicpix / Interactivity.studio

## Requirements

See `requirements.txt` for Python package dependencies.

## Author

Yash Singh  
[LinkedIn](https://www.linkedin.com/in/singhyash2209/)

