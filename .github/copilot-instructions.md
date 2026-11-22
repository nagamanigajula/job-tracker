# Project: Job Application Tracker

## About
A web app to track job applications (company, role, status, date applied, notes).
The developer is learning, so explain changes in simple English.

## Tech stack
- Python 3.13
- FastAPI for the REST API
- SQLModel with SQLite for the database
- pytest for tests

## Folder structure
- app/ → application code (main.py, models.py, database.py, routes/)
- tests/ → all tests, named test_*.py

## Coding rules
- Use type hints on every function.
- Keep functions small and give them clear names.
- Every new endpoint must have at least one pytest test.
- Validate user input and return clear error messages.
- Never put passwords or API keys in code; use environment variables.

## When you finish a change
- Briefly list which files you changed and why.
- Suggest a short git commit message.