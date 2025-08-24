# 📊 n8n Workflow – Automated Lead Evaluation from Google Sheets  

This workflow automates **lead evaluation for companies**.  
Whenever a new lead is added to a Google Sheet, the workflow evaluates the data using an AI model, assigns a **rating**, and generates a **comment** to help prioritize and qualify leads efficiently.  

---

## ⚡ Workflow Overview  

### 🔹 Google Sheets Trigger  
- Watches for new lead entries in a Google Sheet.  

### 🔹 Message a Model (AI Evaluation)  
- Sends lead details to an AI model for evaluation.  
- AI analyzes the information and returns a **rating (1–5)** and a **comment** on lead quality.  

### 🔹 Edit Fields  
- Extracts and formats the AI’s output (rating + comment).  

### 🔹 Merge Node  
- Combines the original lead data with AI-generated evaluation.  

### 🔹 Append or Update Row in Sheet  
- Updates the Google Sheet with the rating and comment alongside the lead data.  

---

## 🛠️ Tech Stack  

- **n8n** – Workflow automation  
- **Google Sheets** – Lead storage  
- **OpenAI (Message a Model)** – AI-based lead evaluation  

---

## 🚀 How It Works  

1. Sales/marketing team enters a new lead in Google Sheets.  
2. Workflow automatically triggers when a new row is added.  
3. AI model reviews lead details → Provides **rating (1–5)** and **comment**.  
4. Results are merged with the original row and updated in the sheet.  
5. Companies get an **instant qualification score**, saving time on manual evaluations.  

---

## 📌 Use Cases  

- **Lead Qualification:** Score leads on a scale to prioritize outreach.  
- **Sales Funnel Optimization:** Identify high-potential leads quickly.  
- **CRM Enhancement:** Add AI-powered evaluation directly into existing pipelines.  
- **Customer Segmentation:** Separate high-quality vs. low-quality leads automatically.  

---
