# 🧠 DeepSeek Code Companion

An AI-powered coding assistant built with **LangChain**, **Ollama**, and **Streamlit**. This tool helps developers with code generation, debugging, and documentation using locally hosted LLMs.

---

## 🚀 Features

- 🧠 Multi-turn conversational AI for code assistance
- 🐍 Python-focused debugging and code generation
- 📚 Code explanation and documentation generation
- 💬 Session memory for context-aware responses
- 🎨 Dark-themed UI with model selection via sidebar
- 🔒 100% local execution using Ollama (no external API calls)

---

## 🧰 Tech Stack

- **Frontend**: Streamlit (with custom CSS)
- **LLM Framework**: LangChain
- **LLM Deployment**: Ollama
- **Models Used**: `deepseek-coder:1.5b`, `deepseek-coder:3b`
- **Language**: Python

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/theshivay/LangchainXdeepseek-r1
cd LangchainXdeepseek-r1
```

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Up Ollama

Install and run Ollama if not already installed:

```bash
# Install Ollama
curl -fsSL https://ollama.com/install.sh | sh

# Run your model
ollama run deepseek-coder:3b
```

> 💡 Tip: You can choose between `deepseek-coder:1.5b` and `3b` depending on system resources.

### 4. Start the App

```bash
streamlit run app.py
```

---

<!-- ## 🖼️ Screenshot

> *(Add a screenshot of your app here)* -->

---

## 📂 Project Structure

```
LangchainXdeepseek-r1/
├── app.py                # Main application
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
```

---

## ✨ Capabilities

- Real-time Python debugging help
- Clear explanation of code logic
- Auto-generates docstrings
- Multi-turn chat with session memory
- No internet dependency after setup

---

## 🤝 Acknowledgements

- [LangChain](https://www.langchain.com/)
- [Ollama](https://ollama.ai/)
- [Streamlit](https://streamlit.io/)
- [DeepSeek](https://github.com/deepseek-ai)

---

## 👤 Author

**Shivam Mishra**  
[GitHub](https://github.com/theshivay) • [LinkedIn](https://www.linkedin.com/in/shivam-mishra-a06654258/)
