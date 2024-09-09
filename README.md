# Detect GPT-Generated Text with BERT
## Overview

This project classifies text as either GPT-generated or human-written using a **BERT-based model**. The model is fine-tuned on a dataset containing examples of both GPT-generated and human-written text.

## Features

- **Text Classification**: Classify text as either GPT-generated or human-written.
- **Pre-trained Model**: Utilize a BERT-based model fine-tuned on relevant datasets.

## Dependencies

This project relies on the following Python packages:

- **`transformers`**: For BERT and other pre-trained models.
- **`torch`**: PyTorch, the deep learning framework used.
- **`scikit-learn`**: For additional machine learning utilities.
- **`numpy`** and **`pandas`**: For data manipulation.


### Data

The dataset used for fine-tuning and evaluation consists of labeled examples of GPT-generated and human-written prompts. You can create your own dataset or use publicly available datasets.

## Installation

To get started, follow these steps:

```sh
git clone https://github.com/your-username/detect-gpt-text-bert.git
cd detect-gpt-text-bert
pip install -r requirements.txt     
