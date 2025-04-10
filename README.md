# RESOLVR: AI Workflow Automation for Indian BPOs

RESOLVR is an AI-powered platform that transforms claims processing workflows in Indian BPOs. It automates customer interactions using real-time transcription, sentiment analysis, and intelligent callback scheduling to deliver faster, cost-effective resolutions—boosting agent productivity and client satisfaction.

## 🚀 Key Features

### 🔁 AI-Powered Automation
- **Sentiment-based Complaint Prioritization** using OpenAI Whisper and transformer models
- **Smart Callback Scheduling** based on urgency, complaint history, and emotional tone
- **Knowledge Base Matching** using RAG + FAISS for instant suggestions

### 🧠 Multimodal AI Agent
- Integrated with **LiveKit** for real-time customer calls
- Automatically handles **follow-ups, escalations, and WhatsApp messages**
- Enables **dynamic call flows** based on customer behavior and complaint data

### 📊 Super Admin Dashboard
- View overall metrics: resolution times, categories, statuses
- Access call transcripts, AI summaries, and quality logs
- Reassign roles and monitor organization-wide performance

### 📍 Complaint & Employee Management
- AI routes complaints to the right team based on domain (Billing, Tech, etc.)
- Reassign tasks manually via the dashboard when needed
- Employee management features with role-based access

---

## 🧪 Architecture Overview

![Architecture Diagram](https://github.com/user-attachments/assets/e5268bda-7730-4058-963f-d9feb2595298)


> RESOLVR follows a modular and scalable design, powered by FastAPI (backend), Next.js (frontend), and PostgreSQL. Integration with Redis, Twilio, FAISS, and Whisper ensures real-time intelligence and rapid responses.

---

## 🛠️ Tech Stack

| Layer | Tech Used |
|-------|-----------|
| Backend | Python (FastAPI) |
| Frontend | Next.js, Tailwind CSS |
| NLP & Voice | OpenAI Whisper, Groq |
| Realtime Comm | LiveKit, Twilio |
| Database | PostgreSQL |
| Vector DB | FAISS |
| Deployment | Render, Vercel |
| Others | Redis, JWT Auth |

---

## 📈 Measurable Impact

- 📉 **30–40%** reduction in callback response time  
- 📈 **15–20%** increase in first-call resolution rate  
- 😃 **25–35%** improvement in client satisfaction  
- ⚙️ **40–50%** decrease in agent workload on repetitive tasks  

---

## 🧩 Modules

1. **Real-time Transcription + Sentiment Analysis**
2. **Smart Complaint Routing**
3. **Callback Scheduling Engine**
4. **Knowledge Base with RAG**
5. **Multimodal AI Voice Agent**
6. **Admin Dashboard & Logs**
7. **Employee Role Management**
8. **WhatsApp Integration**

---

## 🖼️ Screenshots

### Core Screen

<div align="center">
  <img src="https://github.com/user-attachments/assets/0e406c99-c443-4bd1-bc3b-5c85a54b6f0a" alt="Landing Page" style="width: 500px; height: 300px; margin: 10px;" />
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/74d275cb-44ad-42ee-baf9-60589df259a6" alt="Complaint Summary" style="width: 500px; height: 300px; margin: 10px;" />
  <img src="https://github.com/user-attachments/assets/08133bf4-e309-496d-a3c5-0d51713f4b1d" alt="AI Logs" style="width: 500px; height: 300px; margin: 10px;" />
</div>

### Insights & Scheduling

<div align="center">
  <img src="https://github.com/user-attachments/assets/1c428b54-8ad9-4c12-bf96-1e1e056615b8" alt="Analysis" style="width: 500px; height: 300px; margin: 10px;" />
  <img src="https://github.com/user-attachments/assets/f9cfb257-df08-4910-bcdc-c71af1b77edb" alt="Call Scheduler" style="width: 500px; height: 300px; margin: 10px;" />
</div>




---

## 📂 Resources

- [🧠 Architecture Diagram](https://drive.google.com/file/d/16TGU8B_ltaeB9Bbre_US0plsm2t4_Ms5/view?usp=sharing)  
- [📈 Wireframes (Figma)](https://www.figma.com/design/H0tCLG6DonzEDpTMUoHplW/Resolvr?node-id=7-2144&t=00FmwUkJZrAZTb4a-1)  
- [📊 Presentation PDF](./vedant.naik09_EY_Semi_Final.pdf)  
- [💻 GitHub Repo](https://github.com/konduskarsuyash/EY_BPO)  
- [▶️ Demo Video](https://youtu.be/ZvEJBtINRtk)


---

## 📌 How to Run Locally

```bash
# Backend
cd backend
python -m venv env
source env/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
cd frontend
npm install
npm run dev
