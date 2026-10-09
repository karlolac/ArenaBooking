# ArenaBooking 🏟️

Web application for browsing sports venues and booking courts.

Developed using the Django framework.

---

# Features

## 👤 Regular User

* Browse venues and courts
* Book time slots
* Cancel own bookings
* View active and past bookings

## 🛡️ Moderator

* Access to the management dashboard
* Approve / reject booking requests

## 🔧 Admin

* User and group management
* Add new venues and courts
* Overview of the entire application
* Access the booking form
* Cannot place a booking

---

# Test Credentials

| Role | Username | Password |
| --- | --- | --- |
| User | marko | Arenabooking1 |
| Moderator | moderator2 | Arenabooking2 |
| Moderator | moderator | moderator |
| Admin | admin | admin |

---

# Installation (Local)

## 1️⃣ Clone the Repository

```bash
git clone https://gitlab.com/karlolac/django3-arenabooking-website.git
cd ArenaBooking

```

## 2️⃣ Virtual Environment

```bash
python -m venv .venv
.venv\Scripts\activate

```

## 3️⃣ Install Dependencies

```bash
pip install django

```

## 4️⃣ Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate

```

## 5️⃣ Create Superuser (Optional)

```bash
python manage.py createsuperuser

```

## 6️⃣ Run the Server

```bash
python manage.py runserver

```

Application running at:

`[http://127.0.0.1:8000/](http://127.0.0.1:8000/)`

Admin panel:

`[http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)`

---

# Initial Push

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://gitlab.com/karlolac/django3-arenabooking-website.git
git push -u origin main

```

---

# Author

Karlo Lacković

Software Engineering Course Project
