 <p align="center">
  <img src="photo_6136184896825789561_y.jpg"  >
</p>
 



# 🤖 AI-Agent-Sara — Telegram Automation AI Agent (Gemini + Email Sender)

AI-Agent-Sara is an intelligent conversational Telegram bot powered by **Google Gemini AI**.  
The bot acts as a personal AI assistant that can reply smartly to chats and also perform automated tasks such as **sending emails directly from Telegram**.

Sara is built in **Python** and integrates three core systems:
1️⃣ Telegram Bot API  
2️⃣ Google Gemini AI API  
3️⃣ Gmail SMTP Email Automation  

---

## 🚀 Features

| Feature | Status |
|--------|--------|
| Smart AI chat via Gemini | ✅ |
| Dynamic email sending | ✅ |
| User inputs sender email | ✅ |
| User inputs receiver email | ✅ |
| Multi-step conversation automation | ✅ |
| Secure credentials using environment variables | ✅ |

---

## 🧠 How It Works

User Message → Telegram Bot → Python Script → Gemini AI → Bot Reply

/email command → Ask sender email Ask receiver email Ask subject Ask message | ↓ SMTP → Gmail → Email Delivered

Sara becomes not just a chatbot, but a **real task-performing AI agent**.

---

## 🔧 Tech Stack

| Component | Technology |
|----------|------------|
| Programming Language | Python 3 |
| AI Model | Google Gemini Pro |
| Messaging Platform | Telegram Bot API |
| Email Automation | Gmail SMTP |
| Hosting (optional) | Render / Replit / VPS |



---

## 🏗 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/PugazhTheHacker/AI-agent-sara.git
cd AI-agent-sara

2️⃣ Install dependency

pip install requests

3️⃣ Create required environment variables

export BOT_TOKEN="your_telegram_bot_token"
export GEMINI_API_KEY="your_gemini_api_key"
export EMAIL_USER="yourgmail@gmail.com"
export EMAIL_PASS="your_gmail_app_password"

🔹 EMAIL_PASS must be a Gmail App Password, not regular Gmail password.


---

▶️ Run the Bot

python3 ai_agent_sara.py

You’ll see:

🤖 AI-Agent-Sara is now online...

Now open Telegram and chat with your bot.


---

💬 Commands

Command	Description

/start	Introduces Sara and shows features
/email	Starts the email automation process
Text Message	Gemini AI Intelligent reply



---

✨ Email Automation Flow

/email
📧 Enter your email (Sender)
📨 Enter receiver email
📌 Enter subject
✍️ Enter message body
📩 Email sent successfully! 🚀

Works completely inside Telegram — no UI needed.


---

📝 Example Email Body Sent via Sara

Hello,

This email was sent automatically via the AI-Agent-Sara Telegram bot.

Regards,
Sara – Gemini AI Assistant 🤖


---

🌐 Hosting Suggestions

Platform	Notes

Render	Free, 24/7 uptime
Replit	Easiest to start
AWS / DigitalOcean VPS	Full power
Local PC	For development



---

🔐 Security Notes

Never push API keys or passwords to GitHub

Always use .env or environment variables

Never share Gemini API keys or Gmail App Password publicly



---

🛣 Future Upgrade Ideas (Planned)

Feature	Priority

Email attachments (PDF/Images)	⭐⭐⭐⭐
Scheduled email (time delay)	⭐⭐⭐
Memory — save frequently used sender email	⭐⭐⭐
Database logging for email history	⭐⭐
Voice message → AI transcription	⭐⭐



---

🏅 Project Status

AI-Agent-Sara v1.0 — Completed & Stable

Next goal → convert Sara into full AI Automation Suite
with system tools, file processing & threat-intel features.


---

👨‍💻 Developer

Author: Pugazhenthi j
Cyber Security Researcher & Ethical Hacker
Telegram Security + AI Automation Enthusiast


---

⭐ Support the Project

If you like this project, star the repo ⭐
and share ideas for the next update.

gitHub : https://github.com/PugazhTheHacker/AI-agent-sara-cyber-security-.git

