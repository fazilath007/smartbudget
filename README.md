# PocketSmart AI

PocketSmart AI is a FastAPI + Jinja2 + Gemini-powered budget recommendation assistant.

## Features

- User registration
- User login
- JWT authentication
- Logout
- Session management
- Home Interior Planner
- Party Budget Planner
- Jewelry Planner
- Optional outfit image analysis
- Gemini AI integration
- AI fallback recommendations
- Recommendation history
- SQLite database
- Responsive frontend
- Platform search links
- API documentation
- Automated tests

## Project Structure

```text
pocketsmart_ai/
│
├── app/
│   ├── main.py
│   ├── config.py
│   ├── database.py
│   ├── auth.py
│   ├── schemas.py
│   │
│   ├── routers/
│   ├── services/
│   ├── templates/
│   └── static/
│
├── tests/
├── data/
├── uploads/
│
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md