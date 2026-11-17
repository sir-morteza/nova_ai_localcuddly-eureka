# ✨ NOVA AI

**A Local AI Chatbot Powered by Qwen2.5-3B-Instruct**

NOVA AI is an AI chatbot built with Python, Gradio, and the Qwen2.5-3B-Instruct model. It provides a simple, interactive chat interface and runs locally using CPU without requiring an external AI API.

## 🚀 Features

- 🤖 Powered by Qwen2.5-3B-Instruct
- 💬 Interactive chat interface built with Gradio
- 🧠 Conversation history support
- 🌍 Multilingual conversations
- 🎛️ Adjustable temperature and response length
- 💻 CPU-based inference
- 🔌 No external AI API required
- 🧹 Clear conversation functionality

## 🛠️ Technologies

- Python
- Gradio
- llama-cpp-python
- Hugging Face Hub
- Qwen2.5-3B-Instruct (GGUF, Q4_K_M)

## 📦 Model Information

NOVA AI uses:

**Qwen2.5-3B-Instruct-GGUF**

- Model: Qwen2.5-3B-Instruct
- Quantization: Q4_K_M
- Format: GGUF
- Inference: CPU

The model is downloaded from Hugging Face when setting up the project.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
cd NOVA-AI
```

### 2. Install dependencies

```bash
pip install gradio==5.49.1
pip install huggingface_hub psutil
pip install llama-cpp-python
```

For CPU-specific installation, see the [llama-cpp-python installation guide](https://github.com/abetlen/llama-cpp-python).

### 3. Run the application

```bash
python app.py
```

## 💻 Running on Kaggle

NOVA AI can also run in a Kaggle Notebook.

1. Create a new Kaggle Notebook.
2. Enable Internet access.
3. Run the notebook cells in order.
4. Download the Qwen2.5-3B-Instruct GGUF model.
5. Load the model and launch the Gradio interface.
6. Open the generated Gradio link to chat with NOVA AI.

## 📸 Interface

The project provides a simple chat interface where users can:

- Send messages and receive AI responses.
- Continue previous conversations.
- Adjust response creativity.
- Control the maximum response length.
- Clear the chat history.

## 🔮 Future Plans

- [ ] Improve the user interface
- [ ] Add dark mode
- [ ] Add persistent chat history
- [ ] Add support for more AI models
- [ ] Improve response speed
- [ ] Add streaming responses
- [ ] Add document-based conversations

## ⚠️ Requirements

- Python 3.10 or newer
- Internet connection for initial model download
- Sufficient RAM for loading the 3B parameter model
- CPU support

Performance depends on your hardware.

## 📄 License

This project is provided for educational and development purposes. Check the licenses of the model and its dependencies before redistributing them.

## ❤️ Credits

- [Qwen](https://huggingface.co/Qwen) — AI model
- [Gradio](https://www.gradio.app/) — Chat interface
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — Local model inference

---

**Built with ❤️ by the NOVA AI Project**
