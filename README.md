# 🤖 Emotional Support Chatbot — Fine-tuned Mistral 7B using Unsloth

This is an empathetic and conversational emotional support chatbot, fine-tuned on a therapy-focused dataset using the Mistral 7B language model and Unsloth. The goal of this project is to provide a safe, supportive, and emotionally aware AI companion for users experiencing distress or emotional overwhelm.

---

## 🧠 Project Highlights

- 🔹 Fine-tuned **Mistral 7B** using **LoRA** via **Unsloth**
- 🔹 Trained on `vibhorag101/phr_mental_therapy_dataset` for empathetic response generation
- 🔹 Interactive UI built using **Gradio**
- 🔹 Supports natural conversation and active listening patterns
- 🔹 Ideal for demoing LLM fine-tuning with emotional intelligence

---

## 🚀 Live Demo & Hosting

Due to Unsloth’s strict hardware requirement for NVIDIA or Intel GPUs, the Hugging Face Space demo cannot run on the free CPU-only tier.

🔗 **Hugging Face Model Page:**  
https://huggingface.co/your-username/model-name

💻 **Local Demo Available:**  
You can clone this repository and run the chatbot locally if you have GPU access.


---

## 💻 How to Run Locally

```bash
# Step 1: Clone this repository
git clone https://github.com/your-username/emotional-support-chatbot.git
cd emotional-support-chatbot

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run the chatbot
python app.py
