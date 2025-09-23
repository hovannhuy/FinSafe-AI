# 🚀 FinSafe AI  

**A proactive financial assistant on Zalo that personalizes advice, intelligently predicts needs, and seamlessly connects with the Sovico ecosystem.**  

---

## 📑 Table of Contents  
- [📖 Project Summary](#-project-summary)  
- [🚩 Problem & Opportunity](#-problem--opportunity)  
- [💡 Solution & Key Components](#-solution--key-components)  
- [🔮 Development Potential](#-development-potential)  
- [🔄 End-to-End User Flow](#-end-to-end-user-flow)  
- [⚙️ Operating Principles](#️-operating-principles)  
- [🧠 Key Technologies](#-key-technologies)  
- [🛠️ Tech Stack](#️-tech-stack)  

---

## 📖 Project Summary  

FinSafe AI is a groundbreaking initiative to transform **HDBank's chatbot** into a true **Proactive Financial Assistant**, powered by an **AI Agent** on the familiar Zalo platform.  

Instead of sending mass notifications, FinSafe AI focuses on **understanding, predicting, and responding** to the financial needs of each customer.  

The system proactively delivers **personalized suggestions, advice, and offers** via **Zalo/SMS** at the right time, based on the customer’s **Financial Fingerprint** and spending behavior.  

✨ Key breakthrough features include:  
- **Subscription Guardian** – Detects and prevents unwanted recurring fees.  
- **Predictive Shopping Assistant** – Anticipates customer needs and suggests timely offers.  

This experience transforms “annoying” banking messages into **valuable financial insights**, while leveraging the Sovico ecosystem (VietJet, Sovico Resort, HD Saison) to create a unique value loop for both customers and the bank.  

---

## 🚩 Problem & Opportunity  

### ❌ User Problems  
- Overwhelmed by irrelevant, generic banking promotions.  
- Missed genuine financial opportunities.  
- Lack of a proactive tool to protect and optimize personal finance.  

### ❌ Bank Problems  
- Declining effectiveness of customer communication channels.  
- Low conversion rates due to poor personalization.  
- Untapped potential from the Sovico multi-industry ecosystem.  

### ✅ Opportunity  
- Deliver a **persona-driven user experience**.  
- Leverage **calibrated timing** for customer engagement.  
- Build a **differentiated financial assistant** powered by ecosystem integration.  

---

## 💡 Solution & Key Components  

### 1. Personalized AI Consultation & Interaction  
- **Persona-based AI**: Users choose interaction style (Friendly, Professional, Fun).  
- **Smart Spending Optimization**: Tailored combo offers, savings advice, and loan suggestions.  
- **Gamification**: “Complete 10 transactions → Get a VietJet voucher.”  

### 2. Proactive AI Protection & Security  
- **Smart Fraud Detection**: 24/7 monitoring with instant Zalo/SMS alerts.  

### 3. Sovico Ecosystem Integration  
- **Transactions → Rewards**  
  - Open a savings account → 15% VietJet discount.  
  - Reach a spending milestone → Sovico Resort voucher.  

### 4. Technology Architecture & Control  
- **n8n**: Workflow automation and orchestration.  
- **LLM & RAG**: Personalized recommendations with accurate retrieval.  
- **Zalo API**: Direct, user-friendly communication channel.  
- **Strict Control Mechanisms**:  
  - Avoid duplicate service suggestions.  
  - Validate financial conditions before advising.  
  - Escalate complex requests to human agents.  

---

## 🔮 Development Potential  

- **Financial Fingerprint**: Monthly financial summary with engaging personas (e.g., *The Stylish Explorer*, *The Home Builder*).  
- **Service Performance Evaluation**: Analyzes interaction & feedback to improve services.  
- **Subscription Guardian**: Detects and prevents unusual recurring fees.  

---

## 🔄 End-to-End User Flow  

1. User activates **FinSafe AI** in HDBank and selects assistant persona.  
2. Conversation continues seamlessly on **Zalo**.  
3. AI analyzes spending patterns.  
4. The system proactively sends:  
   - **Financial Fingerprint report**  
   - **Subscription Guardian alerts**  
   - **Sovico ecosystem offers**  
5. User engages in chat for more insights.  
6. If the user accepts an offer (e.g., open savings), chatbot provides a **secure deep link** to the HDBank App.  
7. User completes the transaction securely inside the banking app.  

---

## ⚙️ Operating Principles  

1. **Trigger**  
   - Schedule-based (time triggers).  
   - Event-based (webhook via HTTP request).  

2. **Data Collection & Pre-processing**  
   - Sources: Service Register, Savings Account.  
   - Steps: Filtering → Dataset comparison → Custom logic via JavaScript module.  

3. **AI-powered Decision Making (Google Gemini)**  
   - **AI Agent 1**: Initial rule processing & condition updates.  
   - **AI Agent 2**: Data-level processing with RAG:  
     - **Knowledge Base**: Supabase Vector Store + Google Embeddings.  
     - **Contextual Memory**: PostgreSQL Chat Memory for multi-step context retention.  

4. **Task Execution**  
   - Append processed data to spreadsheets.  
   - Trigger external services via HTTP requests.  

---

## 🧠 Key Technologies  

- **LLM**: Google Gemini  
- **AI Architecture**: Retrieval-Augmented Generation (RAG)  
- **Vector Store**: Supabase Vector Store  
- **Memory Database**: PostgreSQL  

---

## 🛠️ Tech Stack  

| Technology | Purpose |
|------------|---------|
| **n8n** | Workflow automation |
| **Zalo API** | Communication with customers |
| **MySQL** | Database |
| **PostgreSQL** | Chat memory storage |
| **Supabase Vector Store** | Semantic retrieval |
| **Google Gemini** | AI-powered insights |
| **Python** | Backend logic |
| **OAuth 2.0 + JWT** | Security & authentication |
