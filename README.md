# Mental Health Support Chatbot (Fine-Tuned)

## Task Objective
The objective of this project is to develop a basic mental health support chatbot that can generate empathetic and emotionally supportive responses for users experiencing stress, anxiety, or emotional distress by fine-tuning a small language model.

## Dataset Used
**EmpatheticDialogues (Facebook AI)**  
A dataset consisting of real human conversations grounded in emotional situations, designed to teach models how to respond empathetically.

## Models Applied
- **DistilGPT2** as the base language model  
- Fine-tuned using **Hugging Face Transformers Trainer API**  
- Training performed with limited batch size and training steps due to Google Colab GPU constraints

## Key Results and Findings
- Training loss decreased during fine-tuning, indicating that the model successfully learned empathetic response patterns from the dataset.
- The fine-tuned model generates more emotionally supportive and gentle responses compared to the base model.
- Due to limited GPU memory and training time, the model did not fully converge, leading to occasional inconsistencies in response quality.
- The project demonstrates a functional proof-of-concept mental health support chatbot under constrained computational resources.
