# AI-Powered Autonomous SQL Agent & Analytics Dashboard

An enterprise-grade, data-driven automation application built with **Python**, **Streamlit**, and **Oracle Database** concepts. This system empowers non-technical business executives (Management, Sales, Finance) to query relational Oracle infrastructures using natural language (English/Chinese) via an AI-driven SQL compiler.

## 🚀 Live Interactive Demo
👉 **[CLICK HERE TO TRY THE LIVE DASHBOARD](此处先留空，等下一小步我们拿到网址后贴在这里)** 
*(Features a built-in interactive simulation mode. No database setup or API keys required to test the core features.)*

## 🌟 Core Business Value
* **Generative AI SQL Translation**: Translates complex plain-text user requests into optimized, dialect-specific Oracle SQL statements via LLM integrations.
* **Autonomous Sandbox Execution**: Safely executes generated queries against Oracle schemas and catches syntax anomalies dynamically.
* **Executive Telemetry & Insights**: Provides high-level business intelligence cards, interactive data charts, and automated AI summary narratives.
* **Downstream Delivery**: Supports instant one-click enterprise data exports to Excel format.

## 🛠️ Tech Stack & Architecture
* **Frontend UI**: Streamlit (Reactive Modern Web Data Framework)
* **Backend Runtime**: Python 3.x
* **AI Cognitive Layer**: OpenAI API / DeepSeek API (REST Endpoints)
* **Data Layer**: Pandas, OpenPyXL, and Oracle `oracledb` (Thin Driver implementation)
* **Data Sandbox**: Features a built-in *Interactive Simulation Mode* allowing fluid interface demonstrations without local database overhead.

## 💻 Local Setup & Deployment
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
   cd YOUR_REPO_NAME
2.Install the required enterprise dependency matrix:
  ```bash
  pip install streamlit pandas requests openpyxl oracledb

3.Launch the reactive agent infrastructure locally:
  ```bash
  py -m streamlit run ai_sql_agent.py
