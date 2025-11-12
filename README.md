# 🦙 LLaMA 3 LoRA Fine-Tuning with Unsloth

This project fine-tunes the `unsloth/Llama-3.2-3B-Instruct` model using LoRA and 4-bit quantization (QLoRA style).

## 🧩 Steps
1. Load pre-trained model via Unsloth
2. Load dataset (`mlabonne/FineTome-100k`)
3. Apply chat templates
4. Fine-tune with `SFTTrainer`
5. Save and run inference

## 🚀 How to Run
```bash
pip install -r requirements.txt
