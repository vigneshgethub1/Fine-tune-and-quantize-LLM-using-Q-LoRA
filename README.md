# Fine-tune-and-quantize-LLM-using-Q-LoRA
This repository contains a complete pipeline for fine-tuning Large Language Models (LLMs) using Hugging Face Transformers, PEFT (Parameter-Efficient Fine-Tuning), and TRL (Transformers Reinforcement Learning). The project leverages LoRA (Low-Rank Adaptation) to efficiently fine-tune models while optimizing memory usage.
Key Features
Dataset Processing: Converts training data from Excel to CSV for model fine-tuning.
Model Loading & Tokenization: Uses AutoModelForCausalLM and AutoTokenizer for flexible adaptation.
Quantization with BitsAndBytes: Reduces memory usage for efficient training.
LoRA-Based Fine-Tuning: Implements LoRA adapters for efficient low-rank adaptation.
Trainer Implementation: Utilizes SFTTrainer for supervised fine-tuning.
