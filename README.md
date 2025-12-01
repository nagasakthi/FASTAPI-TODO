# FastAPI Todo 

A simple and clean Todo REST API built using FastAPI and SQLAlchemy.
This project demonstrates backend development fundamentals including API design, database modeling, and ORM usage.

---

## 🚀 Features
- Create, read, update, and delete todos
- SQLite database integration
- SQLAlchemy ORM models
- FastAPI automatic API documentation
- Clean and modular project structure

---

## 🛠 Tech Stack
- Python
- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn

---

## 📁 Project Structure
FASTAPI-TODO/
├── main.py
├── database.py
├── models.py
├── requirements.txt
└── README.md

yaml
Copy code

---

## ▶️ Run the Project Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/nagasakthi/FASTAPI-TODO.git
cd FASTAPI-TODO
2️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt
3️⃣ Start the server
bash
Copy code
uvicorn main:app --reload
4️⃣ Open API Docs
Swagger UI: http://127.0.0.1:8000/docs

ReDoc: http://127.0.0.1:8000/redoc

📌 Database Model
The Todo model includes:

ID (Primary Key)

Title

Description

Priority

Completion Status

✅ Learning Outcomes
Built RESTful APIs using FastAPI

Designed database schemas with SQLAlchemy ORM

Implemented clean backend architecture

Worked with SQLite for data persistence

🔮 Future Improvements

Add authentication (JWT)

Switch to PostgreSQL

Add pagination and filtering

Dockerize the application

Add unit tests

📄 License

This project is licensed under the MIT License.
