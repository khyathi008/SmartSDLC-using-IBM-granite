# 🧠 SMartSDLC - AI-Enhanced Software Development Lifecycle Assistant

**SMartSDLC** is an intelligent, AI-powered assistant that streamlines every phase of the Software Development Lifecycle (SDLC). Built using IBM's Granite language models and deployed with a Gradio interface on Google Colab, it empowers developers with real-time support for requirement analysis, code generation, testing, debugging, deployment, and documentation.

---

## 🚀 Features

- 🔍 Requirement Analysis with structured outputs
- 💻 Code Generation for Python, Java, Node.js, and more
- ✅ Unit Test Suggestions using frameworks like `unittest` and `pytest`
- 🐞 Debugging Assistance with code fix suggestions
- 📦 Deployment Script Generation (e.g., Dockerfiles, CI/CD workflows)
- 📄 Auto-generated Documentation and READMEs
- 💬 Clean UI with Gradio (prompt suggestions + chat history)

---

## 🛠️ Tech Stack

- [IBM Granite LLMs](https://huggingface.co/ibm-granite)
- [Transformers (Hugging Face)](https://huggingface.co/docs/transformers/index)
- [Gradio](https://www.gradio.app/)
- Python 3.10+
- Google Colab (recommended for GPU support)

---

## 📦 Setup Instructions (Google Colab)

1. Clone this repo or open it in Colab.
2. Install dependencies:
   ```bash
   !pip install gradio transformers accelerate
