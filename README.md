<img width="1680" height="428" alt="Screenshot 2025-11-16 131738" src="https://github.com/user-attachments/assets/c89598bf-5d14-4690-a969-ed33a2e42da0" />🤖 Shopilot – Conversational E-commerce AI Agent

A smart conversational shopping assistant built with **n8n** and **Google Gemini**, fully deployed on **Telegram**.  
Shopilot automates the entire shopping journey — from browsing products to placing orders — with real-time updates and instant confirmations.

---

✨ Project Overview & Purpose

Shopilot is designed for a fictional electronics store, enabling customers to explore products, check availability, and place orders through a friendly chat interface.

The goal is to create a **practical, real-world automation** that:
- Provides **24/7 instant support**
- Reduces **manual workload**
- Improves **customer experience**
- Makes **shopping fun and simple**

---

🚀 Key Features

✔️ Conversational Ordering  
Guides users step-by-step from product selection to checkout inside Telegram.  

✔️ Live Inventory Lookup  
Pulls product details and stock availability directly from **Google Sheets**.  

✔️ Dynamic Product Information  
Descriptions, pricing, images, categories — all fetched instantly.  

✔️ Automated Order Logging  
Every successful order is recorded into Google Sheets with unique Order ID.  

✔️ Multi-Channel Order Confirmation  
After user confirms:
- 💬 Sends Telegram confirmation message  
- 📊 Logs order into Google Sheets  
- 📧 Sends professional HTML confirmation email via Gmail API  

✔️ Guided Data Collection  
Collects quantity, customer name, shipping address, email, and phone number — one at a time.

---

🛠️ Tech Stack & Tools

| Component | Technology |
|----------|------------|
| Automation Platform | n8n |
| AI Model | Google Gemini |
| Messaging | Telegram Bot API |
| Database | Google Sheets |
| Email Automation | Gmail API |

---

📈 Workflow Overview



Shopilot workflow inside n8n:

1️⃣ User sends message on Telegram  
2️⃣ Gemini interprets intent using conversation memory  
3️⃣ Fetches data from inventory sheet when needed  
4️⃣ Collects user order details  
5️⃣ On confirmation: triggers final automation (Sheets + Email + Telegram)  

---

📌 Learning Outcomes

This project demonstrates real-world **AI automation**, including:

- Building multi-step chat workflows
- Integrating AI agents with real-time tools (Sheets, Email, Telegram)
- Working with APIs and OAuth2 authentication
- Applying guided flow automation for e-commerce use cases

---


