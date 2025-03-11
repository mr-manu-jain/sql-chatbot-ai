# Chat with SQL Database using LangChain & Streamlit

This project enables users to **query SQL databases using natural language** through an **AI-powered chatbot** built with **LangChain, SQLDatabaseToolkit, and Streamlit**. It supports both **SQLite** and **MySQL** databases, leveraging **Groq's Llama3-8B model** for intelligent SQL query generation.

## 🚀 Features
- **Natural Language to SQL**: Convert user queries into SQL commands dynamically.
- **Supports Multiple Databases**: Works with **SQLite** (`student.db`) and **MySQL**.
- **Interactive Chat Interface**: Built using **Streamlit** for seamless user interaction.
- **Secure API Integration**: Requires **Groq API key** for AI model inference.
- **Efficient Query Execution**: Uses LangChain's **SQLDatabaseToolkit** for optimized querying.

## 🏗️ Tech Stack
- **Python** (Primary Language)
- **LangChain** (LLM Orchestration)
- **Streamlit** (UI for Chat)
- **SQLDatabaseToolkit** (Database Interaction)
- **Groq API** (LLM Model)
- **SQLite / MySQL** (Database Support)

## 📦 Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/chat-with-sql-db.git
   cd chat-with-sql-db

2. Create a Virtual Environment & Install Dependencies
    ```
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    pip install -r requirements.txt

1. Run the Application
    ```
    streamlit run app.py

## Configuration
Groq API Key: Provide your API key in the Streamlit sidebar.
Database Selection: Choose between SQLite (student.db) or MySQL.
MySQL Connection Details (if applicable): Enter host, username, password, and database name.

### 🎯 How It Works
Select the database type (SQLite or MySQL).
Enter Groq API Key for AI-powered querying.
Type your question (e.g., "Show all students with GPA > 3.5").
The AI agent translates it into SQL and executes it.
View results directly in the chat interface.

### 📝 Example Queries
"What are the top 5 highest-paying jobs?"
"Find all students who scored more than 80% in Mathematics."
"Show total sales for each product in the last quarter."