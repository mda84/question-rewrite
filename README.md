# DisflQA-QuestionRewrite

This repository contains the code and resources for developing a question rewrite model for the Disfl QA benchmark dataset. The objective of this project is to handle noisy questions in conversational workflows and accurately rewrite them to enhance question-answering systems.

## Assignment Overview

- **Objective:** Develop a question rewrite model for the Disfl QA dataset.
- **Datasets:** 
  - Train: [train.json](https://github.com/google-research-datasets/Disfl-QA/blob/main/train.json)
  - Validation: [dev.json](https://github.com/google-research-datasets/Disfl-QA/blob/main/dev.json)
  - Test: [test.json](https://github.com/google-research-datasets/Disfl-QA/blob/main/test.json)
- **Models:** T5, BART, GPT
- **Evaluation Metrics:** Accuracy, BLEU, GLEU

## Repository Structure

- **train.ipynb:** Notebook for training, evaluation, and analysis of T5, BART, and GPT models.
- **test.ipynb:** Notebook for testing the best-performing BART model on the test set.
- **data/**: Directory containing dataset files.
- **models/**: Directory to store trained models and tokenizers.
- **src/**: Contains scripts for data processing, model training, and evaluation.

## Pre-trained Models and Tokenizers

The trained models and tokenizers used in this project are too large to be stored on GitHub. You can download them from the following Google Drive link:

- [Download Pre-trained models](https://drive.google.com/drive/folders/1zrqx6z3vYqz5haGKvfPChg-F7xr6XlXI?usp=sharing)

After downloading, place the DisflQA_Models folder in the `models/` directory within this repository to ensure that the paths align with the code.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/mda84/DisflQA-QuestionRewrite.git
   cd DisflQA-QuestionRewrite
