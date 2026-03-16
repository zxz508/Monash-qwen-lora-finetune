# Monash-qwen-lora-finetune
Fine-tuned Qwen2.5-7B-Instruct on custom-scraped Monash University FAQ data using QLoRA (4-bit quantization) on Kaggle T4 GPU Built a Selenium-based web scraper to extract structured Q&amp;A pairs from Monash official website Reduced trainable parameters to 0.066% of total model size via LoRA (r=8), achieving coherent domain-specific responses
