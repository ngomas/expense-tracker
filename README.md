# Spendly — Expense Tracker

A personal finance tracker built with Flask. Log expenses, see where your money goes by category, and filter spending by time period.

> **Status:** work in progress. The landing, register and login pages are in place; authentication, the database and expense management are being built step by step.

## Tech stack

- **Backend:** Python 3.9+, Flask 3
- **Database:** SQLite
- **Frontend:** Jinja2 templates, plain CSS and JavaScript
- **Testing:** pytest, pytest-flask

## Getting started

```bash
# Clone the repository
git clone https://github.com/ngomas/expense-tracker.git
cd expense-tracker

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

Then open http://127.0.0.1:5001 in your browser.

## Running tests

```bash
pytest
```

## Project structure

```
expense-tracker/
├── app.py              # Flask app and routes
├── database/
│   └── db.py           # SQLite connection, schema and seed data
├── templates/          # Jinja2 HTML templates
├── static/
│   ├── css/style.css
│   └── js/main.js
└── requirements.txt
```

## Roadmap

- [ ] Database setup (users and expenses tables)
- [ ] User registration and login
- [ ] Logout
- [ ] Profile page
- [ ] Add expenses
- [ ] Edit expenses
- [ ] Delete expenses
- [ ] Category breakdowns and monthly summaries
- [ ] Filter by date range
