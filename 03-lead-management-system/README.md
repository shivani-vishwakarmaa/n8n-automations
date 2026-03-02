# 🎯 End-to-End Lead Management & Qualification Engine
A 24/7 automated system designed to capture, qualify, and route leads with zero manual effort.
* 🎥 Live Demo & Workflow Screenshots  👉 [View Here](https://drive.google.com/drive/folders/1aFH0duu2Av_dSMaoi4eBLNlLklDGbKpp?usp=drive_link)


### ⚠️ The Problem
Inbound leads often go cold due to delayed responses. Without a qualification layer, sales teams waste time on "tire kickers" instead of high-intent prospects, leading to messy CRM data and lost revenue.

### 🛠️ Tech Stack
- **Orchestration:** n8n (Self-hosted)
- **Intelligence:** OpenRouter (LLM Decision Engine)
- **Database:** Google Sheets
- **Notifications:** Slack & Professional Email
- **CRM Integration:** Automated Contact Creation/Search

### 🧩 System Logic (How it Works)
1. **Instant Capture:** New leads are picked up immediately via Webhooks.
2. **AI Qualification:** An LLM analyzes the lead's intent and categorizes them into a "Temperature Scale" (Hot, Warm, or Cold).
3. **Smart Routing:** - **Hot Leads:** Triggers an immediate Slack alert to the owner for manual follow-up.
   - **Warm/Cold Leads:** Enters an automated email nurturing sequence.
4. **Data Integrity:** The system automatically checks for duplicates in the CRM before creating or updating a contact record.

### 💡 Business Value
- **Immediate Response:** Every lead feels acknowledged instantly with an AI-personalized message.
- **High-Quality Focus:** Sales teams only spend time on qualified "Hot" leads.
- **Clean Data:** Eliminates duplicated or unstructured lead data through automated cleanup.
