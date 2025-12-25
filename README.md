🛡️ Insurance Claim Assistant
AI-Powered Policy Matching & Claim Analysis System
📌 Project Overview

The Insurance Claim Assistant is a web-based AI application that helps analyze insurance claims by matching them against uploaded policy documents.
It uses Natural Language Processing (NLP) and semantic similarity to identify relevant policy clauses and assist claim verification.

This project demonstrates how AI can improve claim assessment accuracy, speed, and transparency.

🎯 Key Features

📂 Upload insurance policy documents (PDF)

🧠 AI-based semantic search using embeddings

🔍 Match claim descriptions with policy clauses

📊 Display relevant policy matches with confidence

🎨 Professional, modern UI

⚡ Built using Streamlit for rapid deployment

🧱 Tech Stack
Layer	Technology
Frontend UI	HTML, CSS
Web Framework	Streamlit
AI / NLP	Sentence Transformers
Vector Search	Local Vector Store
Backend	Python
PDF Handling	PyPDF
Environment	Python Virtual Environment
📁 Project Structure
appian-main/
│
├── frontend/
│   ├── demo_app.py        # Main Streamlit app
│   ├── index.html         # UI layout
│   ├── style.css          # UI styling
│
├── simple_vector_store.py # Vector search logic
├── knowledge_ingestion.py # Policy ingestion
├── venv/                  # Virtual environment
├── README.md              # Project documentation

🚀 How to Run the Project (VS Code)
1️⃣ Clone the Repository
git clone https://github.com/YOUR-USERNAME/insurance-claim-assistant.git
cd insurance-claim-assistant

2️⃣ Create & Activate Virtual Environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install Dependencies
pip install streamlit sentence-transformers transformers tf-keras

4️⃣ Run the Application
cd frontend
streamlit run demo_app.py

5️⃣ Open in Browser
http://localhost:8501
