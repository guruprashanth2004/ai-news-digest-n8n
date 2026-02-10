# 🧠 AI News Digest Automation (n8n)

This project is an end-to-end automation workflow built using **n8n** that fetches the latest AI news, summarizes it using a **free Hugging Face model**, and sends a daily digest via **Gmail**.

Built as a hands-on learning project to understand workflow automation and AI API integration.

---

## 🚀 Features

- ⏰ Scheduled trigger using n8n  
- 🌐 Fetches real-time AI news via NewsAPI  
- 🤖 Summarizes articles using Hugging Face Inference API (no paid models)  
- 📧 Automatically emails summarized news  
- ⚙️ Fully automated pipeline  

---

## 🏗 Workflow Architecture

Schedule Trigger  
→ NewsAPI (HTTP Request)  
→ Hugging Face Summarizer (HTTP Request)  
→ Gmail SMTP  

---

## 🛠 Tech Stack

- n8n (workflow automation)
- NewsAPI
- Hugging Face Inference API
- Gmail SMTP

---

## 📸 Screenshot

(Add your n8n workflow screenshot here)

---

## 🧑‍💻 What I Learned

- Building event-driven automation workflows
- API orchestration using n8n
- AI inference without OpenAI
- Handling JSON responses
- SMTP email integration

---

## 📦 Setup Overview

1. Run n8n (Docker or Cloud)
2. Create NewsAPI key
3. Create Hugging Face access token
4. Configure HTTP Request nodes
5. Configure Gmail SMTP
6. Activate workflow

---

## 📄 Resume Line

Built an automated AI news digest using n8n, integrating external APIs and Hugging Face inference models to summarize daily AI news and deliver scheduled email reports.

---

## 🌱 Future Improvements

- WhatsApp delivery
- Google Sheets logging
- Duplicate article filtering
- Topic selector

---

Built while learning n8n 🚀
