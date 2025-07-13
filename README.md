# 🤖 Smart Q&A Chatbot with Semantic Search & Gradio UI

This project is a smart **Question & Answer chatbot** that uses:
- 🧠 **Semantic Search** to find the most relevant knowledge paragraph,
- 📚 A manually curated **custom knowledge base** (100+ entries),
- 🤖 A Hugging Face **question-answering model** (`distilbert-base-uncased-distilled-squad`),
- 💬 And an interactive **Gradio chatbot interface**.

Unlike traditional bots, this one doesn't rely on static rules — it finds the best paragraph from your domain-specific knowledge and generates answers dynamically.

---

## 🔍 Features

- ✅ Fully functional **Q&A chatbot interface** using [Gradio](https://gradio.app)
- ✅ **Custom knowledge base** (you can add hundreds of facts manually)
- ✅ Uses **semantic similarity** (via Sentence Transformers) to retrieve the most relevant context
- ✅ Built using **free and open-source tools** (no paid API like OpenAI)
- ✅ Clean, modular, and well-documented code

---

## 📌 How It Works

1. The user asks a question via the chat.
2. The system uses **sentence embeddings** to find the most similar paragraph from the knowledge base.
3. That paragraph is fed into a **pretrained QA model** that extracts the answer.
4. The answer is displayed in a chatbot interface using **Gradio**.

---

## 🧠 Tech Stack

| Component               | Library / Model                                      |
|------------------------|------------------------------------------------------|
| Semantic Search         | `sentence-transformers` (`all-MiniLM-L6-v2`)         |
| Question Answering      | `transformers` (`distilbert-base-uncased-distilled-squad`) |
| UI / Chatbot Interface  | `gradio`                                             |
| Language                | Python                                               |
| Environment             | Google Colab                                         |

---



