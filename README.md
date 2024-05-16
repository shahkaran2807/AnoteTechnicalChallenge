Overview
This repository contains the code and instructions for training and testing a fine-tuned model for answering finance-related questions. The model is trained using the Llama 3 8b architecture from UnSloth, fine-tuned on a combined dataset using the LORA technique (Instruction, Context, Answer).

Files
Model Training and Fine-Tuning:

This Python file combines two given datasets.
It utilizes the Llama 3 8b architecture from UnSloth.
Fine-tuning is performed on the dataset using the LORA technique, with the format: Instruction, Context, Answer.
After successful training, the model is uploaded to Hugging Face for further use.
Model Testing:

This Python file downloads the fine-tuned model from Hugging Face.
It loads the test data file and iteratively feeds each row to the model for answering.
The output is collected for evaluation and analysis.

Note:
The test dataset contains more than 600+ questions. My model is able to answer 100 of them and throws error after that due to bandwidth and resources constraints. I am still working on improving it.
