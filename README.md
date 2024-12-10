Legal Document Analysis Using Legal-BERT

Overview

This project leverages Legal-BERT, a pre-trained language model fine-tuned specifically for legal texts, to perform Named Entity Recognition (NER)
 It identifies key entities such as sections, acts, and judgments from Indian legal documents, providing a structured way to analyze complex legal data.

 Key Features

Fine-tunes Legal-BERT on custom Indian legal datasets.
Extracts and labels legal entities such as Sections, Acts, and Judgments.
Outputs predictions in a structured and interpretable format.
Designed for scalability to handle large datasets.

Steps to Use:

Install dependencies: transformers, datasets, torch.
Prepare your dataset in JSON format with text and entities.
Train the model using the provided training script.
Test the model with new legal documents.

Requirements:

Python 3.10+
Google Colab or GPU-enabled environment


