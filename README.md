# 🌐 Web Content Summarization using Llama3.2-3B (Local Ollama Deployment)

## 📌 Project Overview
This project automates the retrieval and summarization of web content using AI. The system fetches relevant data from:

- 🏛 **Wikipedia** – Extracts structured content using BeautifulSoup.
- 🔍 **Top 2 Search Results** – Uses Google Search to fetch the most relevant pages.

The extracted content is summarized using **Llama3.2-3B**, running locally via **Ollama**.

---

## ⚙️ Methodology

1️⃣ **User Input**: The user provides a topic.
2️⃣ **Data Retrieval**:
   - Wikipedia content is fetched using BeautifulSoup.
   - The top 2 search results are identified via Google Search API and scraped using Selenium.
3️⃣ **Content Processing**:
   - Removes unnecessary elements (scripts, styles, inputs).
   - Merges Wikipedia and search results for a comprehensive summary.
4️⃣ **Summarization**:
   - A structured prompt guides the AI.
   - **Llama3.2-3B**, running locally on **Ollama**, generates a markdown-formatted summary.
5️⃣ **Output Display**: The summary is displayed in markdown format.

---

## 🚀 Features

✅ **Locally Hosted AI Inference** – Ensuring privacy and performance with Ollama.
✅ **Multi-Source Aggregation** – Improves accuracy by combining multiple sources.
✅ **Automated Web Scraping** – Wikipedia and Google Search are seamlessly integrated.
✅ **AI-Powered Summaries** – Well-structured markdown output.
✅ **No External API Costs** – Fully open-source and self-contained.

---

## 🔗 Useful Links

- [Ollama Website](https://ollama.ai/)
- [Llama3 Model Details](https://ollama.ai/library/llama3)
- [Google Search Python API](https://pypi.org/project/google-search-results/)
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Selenium Documentation](https://www.selenium.dev/documentation/)

---

## 📢 Notes

⚠️ **Ensure Ollama is installed and running locally** before executing the script.
⚠️ **Google Search scraping might require API key or adjustments** based on restrictions.
⚠️ **Some websites may block scraping; use with caution.**

💡 _For best results, ensure a stable internet connection and appropriate permissions._

---

## 🛠 Installation

```bash
pip install beautifulsoup4 selenium google-search-results
```

Ensure Ollama is set up correctly:

```bash
ollama run llama3.2
```

---

## 📜 License
This project is licensed under the MIT License.

👨‍💻 _Happy Coding!_ 🚀
