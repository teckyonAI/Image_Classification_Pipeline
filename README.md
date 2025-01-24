# Image Classification Pipeline: Build, Train, and Deploy ML Models

This repository provides a robust pipeline for image classification tasks. It includes tools for data processing, model training, evaluation, and deployment, making it ideal for end-to-end machine learning workflows.

## Features
- **Data Processing**: Prepares and augments image datasets for improved model performance.
- **Model Training**: Implements configurable training pipelines for various architectures.
- **Evaluation and Metrics**: Tracks model performance with detailed metrics and visualizations.
- **Deployment-Ready**: Supports model packaging for deployment in production environments.

## Installation

To set up and run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/teckyonAI/Image_Classification_Pipeline.git

2. Navigate to the project directory:
   ```bash
   cd Image_Classification_Pipeline

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt

4. Set up the project configuration:
   - Edit the `config` files to adjust paths, hyperparameters, or dataset settings as needed.

## Usage

1. Configure the Pipeline:
   - Update `params.yaml` to customize data preprocessing, training, and evaluation parameters.
2. Execute the pipeline using `dvc`:
    ```bash
    dvc repro
3. Model Training: The training script automatically saves checkpoints and logs metrics for each epoch.
4. Evaluation: Use the evaluation module to generate confusion matrices, accuracy reports, and loss graphs.

## Deployment

This project is configured to deploy trained models using `setup.py`. To deploy a trained model:
1. Package the model:
    ```bash
    python setup.py sdist
2. Use the package in your production environment or deploy it using a cloud platform.

## Contribution

Contributions are welcome! Here's how you can contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed explanation of the changes.

