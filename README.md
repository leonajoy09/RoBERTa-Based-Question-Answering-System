This project implements a Question Answering (QA) system using RoBERTa, a state-of-the-art NLP model fine-tuned on the SQuAD2 dataset. The system processes questions and context to extract relevant answers using PyTorch and the Hugging Face Transformers library.


Key Features:
✅ RoBERTa-Based QA Model – Uses deepset/roberta-base-squad2 for natural language understanding.
✅ Tokenization & Model Inference – Converts input text into tokens and extracts answers based on start and end logits.
✅ Multiple Input Handling – Processes multiple questions with different contexts.
✅ Pipeline for Simplicity – Utilizes the Hugging Face pipeline for an easier and more efficient inference process.


How It Works:
Input a question and context, tokenize the text, and pass it through the RoBERTa model.
Identify the answer span using the model’s start and end logits.
Extract and decode the answer from the tokenized input.
Use the pipeline function to simplify the process and get an easy-to-use response format.


Tech Stack:
Model & Processing: PyTorch, Transformers (Hugging Face)
Pretrained Model: deepset/roberta-base-squad2
Implementation: Python
