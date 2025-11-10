# Task Manager Web Application

This is a simple task management web application built using Python. It allows users to register, log in, create tasks, and manage them (mark as complete, update, or delete).

The project demonstrates Python-based full stack development using:

- **Backend:** Flask (RESTful API)
- **Frontend:** Streamlit
- **Database:** SQLite (development) → PostgreSQL (optional for deployment)

---

## 🔧 Features

- User authentication (login/register)
- CRUD operations for personal tasks
- View all tasks and completion status
- Lightweight UI with Streamlit
- Simple and scalable architecture
- API tested with Postman
- (Optional) Real-world data integration using JSON/CSV or APIs

---

## 📦 Technologies Used

| Component     | Technology     |
|---------------|----------------|
| Programming   | Python 3       |
| Backend       | Flask          |
| Frontend      | Streamlit      |
| Database      | SQLite / PostgreSQL |
| API Testing   | Postman        |
| Deployment    | Render / Streamlit Cloud |
| Docs/API Spec | Swagger / OpenAPI |

---

## 🛠 How to Run

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run Flask backend
python app.py

# In another terminal, run Streamlit frontend
streamlit run frontend.py






task-manager/
│
├── app.py                # Flask backend
├── frontend.py           # Streamlit frontend
├── models/               # Database models
├── templates/            # HTML templates (if used)
├── static/               # CSS/JS files
├── requirements.txt      # Dependencies
└── README.md             # This file
