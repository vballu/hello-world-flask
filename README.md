# Hello World Flask

A simple Flask web application that displays "Hello World!" in the browser, designed for deployment on Clever Cloud.

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the application:
   ```bash
   python main.py
   ```

3. Open your browser and navigate to `http://localhost:8080`

## Deployment

This project is configured for deployment on [Clever Cloud](https://www.clever-cloud.com/):

- Uses Python 3.12
- Dependencies managed via `requirements.txt`
- Runs on port 8080 with host 0.0.0.0
- Flask app object named `app` for automatic detection

## Project Structure

- `main.py` - Flask application entry point
- `requirements.txt` - Project dependencies
- `pyproject.toml` - Python project configuration
- `.python-version` - Python version specification