# Python Demo App

A simple FastAPI application with two endpoints:

- `/` returns a welcome message
- `/hello/{name}` returns a personalized greeting

## Requirements

- Python 3.13+
- `pip`

## Local Setup

1. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Run the App

Start the API with Uvicorn:
