# Honeypot Demo

A simple Flask app with login, registration, and a clean UI. Uses SQLite for storage.

## Run on your local machine

### 1. Clone or open the project

```bash
cd honeypot-demo
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv .venv
```

Activate it:

- **macOS / Linux:** `source .venv/bin/activate`
- **Windows (Cmd):** `.venv\Scripts\activate.bat`
- **Windows (PowerShell):** `.venv\Scripts\Activate.ps1`

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the app

```bash
python app.py
```

The server runs at **http://127.0.0.1:5000**. Open that URL in your browser.

### 5. Use the app

- **Home** shows the login page.
- Click **Register** to create an account (username and password).
- After registering, sign in on the login page.
- Once logged in, you’ll see a welcome message with your username and a sign-out link.

The SQLite database file `app.db` is created automatically in the project folder on first run.
