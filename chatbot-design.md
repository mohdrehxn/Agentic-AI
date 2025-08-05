# 🧠 Chatbot Design Document

This file describes the logic, structure, and use case of the chatbot built using **IBM Watsonx Assistant**.

---

## ✅ Use Case

**Name:** Research Agentic AI  
**Goal:** A Research Agent designed to assist with academic and scientific research tasks. 

---

## 🔁 Dialog Flow Overview

- Greet user → Ask intent → Route to:
  - Password Reset Guide
  - Software Request Form
  - Device Troubleshooting Help
  - End Conversation (Thank You)

---

## 🧠 Intents (examples)

- #greet
- #password_reset
- #software_request
- #thank_you

---

## 💬 Entity Examples

- @software: [Zoom, Slack, MS Teams]
- @device: [Laptop, Phone, Tablet]

---

## 🛠 Tools Used

- Watsonx Assistant (Dialog Builder)
- Prompt Lab (Watsonx.ai) for smart response generation (optional)
- IBM Cloud Console (project management)

---

## 📷 Screenshots

See `C:\Users\Mohd Rehan\Downloads\Amaan\New folder\watsonx-chatbot\assets\Picture1.jpg` `C:\Users\Mohd Rehan\Downloads\Amaan\New folder\watsonx-chatbot\assets\Picture2.png` for visual examples.
