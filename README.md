# 🚀 Scheduler Tracker (Django Project)

A personal web-based scheduler + task + project tracker with progress visualization.

---

# 📦 Project Setup (Run Anywhere)

## 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/SchedulerProject.git
cd SchedulerProject
```

---

## 2️⃣ Create Virtual Environment

```
python -m venv venv
```

Activate:

### Windows (PowerShell)

```
.\venv\Scripts\Activate.ps1
```

### Windows (CMD)

```
venv\Scripts\activate
```

---

## 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

---

## 4️⃣ Apply Migrations

```
python manage.py migrate
```

---

## 5️⃣ Create Admin User (Optional but Recommended)

```
python manage.py createsuperuser
```

---

## 6️⃣ Run Server

```
python manage.py runserver
```

Open in browser:
http://127.0.0.1:8000/

---

# ⚙️ Tech Stack

* Python 3.10+
* Django 5.x
* SQLite (default DB)

---

# 📁 Project Structure

```
SchedulerProject/
│
├── config/        # Django project settings
├── manage.py      # Django CLI
├── requirements.txt
├── README.md
└── venv/ (ignored)
```

---

# 🔁 Daily Development Workflow

```
git add .
git commit -m "your message"
git push
```

---

# 🔄 Run on Another PC (Quick Commands)

```
git clone <repo-url>
cd SchedulerProject
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

# 📌 Notes

* Virtual environment (`venv`) is not pushed to Git
* Database (`db.sqlite3`) is local only
* Use `requirements.txt` to recreate environment

---

# 🚧 Upcoming Features

* Task Tracker
* Project Progress (%)
* Dashboard with charts (Bar / Pie)
* Login System
* OTP Verification (later phase)
