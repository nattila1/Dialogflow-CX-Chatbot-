# 🏦 Enterprise-Level AI Loan Assistant with Dialogflow CX

This repository contains the resources and architecture for building a sophisticated, generative AI-powered virtual agent designed for a realistic banking scenario. Using Google Cloud's Conversational Agents (formerly Dialogflow CX) and the Playbooks framework, this project demonstrates how to move beyond basic chatbot limitations to create a flexible, task-oriented assistant.

*For detailed step-by-step instructions and the full source code for the Python functions and OpenAPI schemas, please refer to the [associated blog post](https://bestflow.io/blog/posts/how-to-create-an-enterprise-level-ai-chatbot-for-answering-your-business-question-perform-custom-actions-and-collect-leads-to-google-sheets/).*

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/0pQBq_DgSdQ/0.jpg)](https://www.youtube.com/watch?v=0pQBq_DgSdQ)

## 🚀 Key Features

* **🧠 Brains & Logic:** Powered by the Playbooks framework, allowing for natural, unpredictable human conversations that stay on track.
* **📖 Instant Knowledge:** Uses a **Google Cloud Storage** to scan your business documents, providing grounded, accurate answers instantly.
* **🔢 Precision Math:** Leverages a custom **Python-based Google Cloud Function** to perform complex loan calculations with 100% accuracy"
* **📊 Lead Generation Machine:** Automatically captures customer inquiries and syncs them directly to a **Google Sheet** for seamless CRM integration.
* **🌐 Professional Deployment:** Ready for the web with a customizable UI and enterprise-grade environment management.

---

The goal of this tutorial is to build a **Loan Assistant** for a fictional bank ("Best Flow Loans"). The agent is capable of handling unpredictable user turns, providing real-time financial calculations, and managing lead generation.

### Key Functionalities:
* **Dynamic Product Inquiries:** Answering specific questions about loan products using a structured Knowledge Base. 
* **Real-time Calculations:** Performing live loan payment calculations via custom Python logic.
* **Automated Lead Capture:** Gathering customer information and instantly saving it to a Google Sheet for business follow-up. 

## Tech Stack

* **Conversational AI:** Google Cloud Conversational Agents (Dialogflow CX) - Playbooks.
* **Backend:** Google Cloud Functions (Python 3.x). 
* **Data Storage:** Google Cloud Storage (for structured data) and Google Sheets (for CRM/Leads). 
* **Integration:** OpenAPI schemas for tool connectivity and Dialogflow Messenger for web deployment.

## What You Will Learn

By following this project, you will master the following enterprise AI concepts:

1.  **Playbook Orchestration:** How to use a "Default Playbook" as a central orchestrator to route users between specialized task-oriented playbooks.
2.  **Standardized Communication:** Configuring Input and Output parameters to reliably transfer technical data (like loan amounts and terms) across different Playbook states. 
3.  **RAG (Retrieval-Augmented Generation):** Connecting the LLM to a Data Store (Google Cloud Storage) to provide grounded answers based on your own business documentation.
4.  **Custom Tooling:** Building and connecting external APIs via Cloud Functions to extend the agent's capabilities with custom code.
5.  **Behavior Fine-tuning:** Using manual examples to control agent responses, enforce specific formatting (e.g., bulleted lists), and manage hand-offs.
6.  **Production Deployment:** Creating versions, setting up environments, and embedding the chatbot into a live website.
