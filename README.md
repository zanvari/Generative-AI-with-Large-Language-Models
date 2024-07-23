# [Generative AI with Large Language Models (Coursera)](https://www.deeplearning.ai/courses/generative-ai-with-llms/)
In the course on Generative AI with Large Language Models (LLMs), you'll gain a fundamental understanding of how generative AI operates and how to implement it in practical applications.

By taking this course, you'll learn to:
- Gain a thorough understanding of generative AI and the key steps in the LLM lifecycle, including data gathering, model selection, performance evaluation, and deployment.
- Explain the transformer architecture, its training process, and how fine-tuning adapts LLMs to specific use cases.
- Optimize the model's objective function using empirical scaling laws considering dataset size, compute budget, and inference requirements.
- Implement advanced training, tuning, inference, tools, and deployment methods to enhance model performance within project constraints.
- Explore the challenges and opportunities of generative AI in business through insights from industry researchers and practitioners.


## Week 1

### Objectives:
- Explore model pre-training and evaluate the benefits of ongoing pre-training compared to fine-tuning.
- Clarify the terms Generative AI, large language models, and prompt, and explain the transformer architecture that drives LLMs.
- Detail the stages of a generative AI model lifecycle using LLMs and examine the constraints that influence decisions at each stage.
- Address the computational challenges encountered during model pre-training and identify methods to efficiently minimize memory usage.
- Define scaling laws and explain the laws related to LLMs concerning training dataset size, compute budget, inference requirements, and other factors.

### Lab:
In this lab, you will do the dialogue summarization task using generative AI. You will explore how the input text affects the output of the model, and perform prompt engineering to direct it towards the task you need. By comparing zero shot, one shot, and few shot inferences, you will take the first step towards prompt engineering and see how it can enhance the generative output of Large Language Models.  

[Lab 1 - Generative AI Use Case: Summarize Dialogue](https://github.com/zanvari/Generative-AI-with-Large-Language-Models/blob/main/Week_1/Lab_1_summarize_dialogue.ipynb)

### Quiz:
[Week 1 quiz](https://github.com/zanvari/Generative-AI with-Large-Language-Models/blob/main/Week_1/Week_1_Quiz.md)

## Week 2

### Objectives:
- Explain how fine-tuning with instruction-based prompt datasets can enhance performance on multiple tasks.
- Define catastrophic forgetting and discuss strategies to mitigate it.
- Define Parameter-efficient Fine Tuning (PEFT).
- Describe how PEFT reduces computational costs and addresses catastrophic forgetting.
- Discuss how instruction-based prompt dataset fine-tuning can improve LLM performance on various tasks.

### Lab:
In this lab, you will fine-tune an existing LLM from Hugging Face for enhanced dialogue summarization. You will use the FLAN-T5 model, which provides a high quality instruction tuned model and can summarize text out of the box. To improve the inferences, you will explore a full fine-tuning approach and evaluate the results with ROUGE metrics. Then you will perform PEFT fine-tuning, evaluate the resulting model and see that the benefits of PEFT outweigh the slightly-lower performance metrics.

[Lab 2 - Fine-tune a generative AI model for dialogue summarization](https://github.com/zanvari/Generative-AI-with-Large-Language-Models/blob/main/Week_2/Lab_2_fine_tune_generative_ai_model.ipynb)

### Quiz:
[Week 2 quiz](https://github.com/zanvari/Generative-AI-with-Large-Language-Models/blob/main/Week_2/Week_2_Quiz.md)

## Week 3

### Objectives:
- Explain how RLHF leverages human feedback to enhance the performance and alignment of large language models.
- Detail how data collected from human labelers is utilized to train a reward model for RLHF.
- Define chain-of-thought prompting and describe its role in enhancing LLMs' reasoning and planning capabilities.
- Discuss the challenges LLMs encounter due to knowledge cut-offs and explain how information retrieval and augmentation methods can address these issues.

### Lab:
In this lab, you will fine-tune a FLAN-T5 model to generate less toxic content by Facebook's hate speech reward model. The reward model is a binary classifier that predicts either "not hate" or "hate" for the given text. You will use Proximal Policy Optimization (PPO) to fine-tune and detoxify the model.  

[Lab 3 - Fine-tune FLAN-T5 with reinforcement learning to generate more-positive summaries](https://github.com/zanvari/Generative-AI with-Large-Language-Models/blob/main/Week_3/Lab_3_fine_tune_model_to_detoxify_summaries.ipynb)

### Quiz:
[Week 3 Quiz](https://github.com/zanvari/Generative-AI-with-Large-Language-Models/blob/main/Week_3/Week_3_Quiz.md)
