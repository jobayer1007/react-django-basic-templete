```markdown
# Project Setup

## Clone the Repository

Clone the repo in a fresh directory.

## Backend Installation
```

1. **Navigate to the Backend Directory**

   ```sh
   cd backend
   ```

2. **Check Python Version**

   ```sh
   python --version
   ```

   The project requires Python version 3.10.8.

3. **Create a Virtual Environment**

   ```sh
   python -m venv .venv
   ```

   Note: You can change `.venv` to any name of your choice.

4. **Activate the Environment**

   - For Windows:
     ```sh
     .\.venv\Scripts\activate.bat
     ```
   - For Mac:
     ```sh
     source .\.venv\Scripts\activate
     ```

   **Note:** For Windows and VSCode terminal, close/kill the current terminal and reopen it. There will be `(.venv)` displayed at the terminal if the environment is activated successfully.

5. **Install Dependencies**

   ```sh
   pip install -r requirements.txt
   ```

6. **Apply Migrations**

   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```

7. **Run the Server**

   ```sh
   python manage.py runserver
   ```

   Once the server is running successfully, to test register a new user, go to:

   ```
   http://127.0.0.1:8000/api/user/register/
   ```

   Keep the backend server running.

## Frontend Installation

1. **Navigate to the Frontend Directory**

   ```sh
   cd frontend
   ```

2. **Install Frontend Dependencies**

   ```sh
   npm install
   ```

3. **Run the Frontend**

   ```sh
   npm run dev
   ```

   Once the server is running successfully, to register your first user, go to:

   ```
   http://localhost:5173/register
   ```
