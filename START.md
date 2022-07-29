# QUICK_START

1. Clone project
2. Open a project in PyCharm with default settings
3. Create a virtual venv(`settings` -> `project` -> `interpreter`)
4. Update pip:
   ```
   pip install --upgrade pip
   ```
5. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
6. Migrate database and create super user:
    ```
   python manage.py migrate
   python manage.py create_admin
   ```
7. Create run configuration in PyCharm(file `manage.py`, option `runserver`)

