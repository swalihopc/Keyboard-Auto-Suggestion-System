# 🧠 Keyboard Auto-Suggestion System (NLP + Flask)

This project implements a **real-time word suggestion system** using **Natural Language Processing (NLP)** and the **Flask web framework**. The system processes a large text corpus (e.g., Sherlock Holmes stories) and provides intelligent suggestions based on user input using **Jaccard similarity** and **word frequency probability**.

---

## 🚀 Key Features

- 🔤 Auto-suggests similar words as you type
- 🔍 Uses **Jaccard similarity (q=2)** for fuzzy matching
- 📊 Ranks suggestions based on **frequency & similarity**
- 🧠 Built with **pure Python NLP** — no pretrained models
- 🌐 Powered by a lightweight **Flask web app**
- 📄 Based on classic text corpus (customizable)

---

## 🛠 Tech Stack

| Layer      | Tools / Libraries                          |
|------------|---------------------------------------------|
| Backend    | Python 3, Flask                             |
| NLP        | `textdistance`, `re`, `collections.Counter` |
| Frontend   | HTML + Jinja2 (via Flask `render_template`) |
| Data       | Raw `.txt` file as corpus (`story.txt`)     |
| UI Hosting | Localhost via `flask run`                   |

---

<img width="1886" height="997" alt="image" src="https://github.com/user-attachments/assets/ae42fbc7-5c43-4ca4-8307-8f458e8943a5" />
