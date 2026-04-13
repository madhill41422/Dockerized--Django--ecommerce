![Python](https://img.shields.io/badge/Python-3.x-blue)
![Django](https://img.shields.io/badge/Django-Framework-green)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)

# 🛒 Dockerized Django E-Commerce Application

This is a Dockerized full-stack e-commerce web application built using Django.  
It supports product browsing, user authentication, cart management, and admin-based product control.  
The project demonstrates real-world web development and containerization practices.
---

## 🚀 DevOps Features

- Dockerized Django application
- Environment-based dependency management
- Ready for cloud deployment (AWS / Azure)
- Structured project layout
- Production-ready container support

---

## 🧠 Tech Stack

| Technology | Role |
|------------|------|
| Django     | Backend Framework |
| SQLite3    | Default Database |
| HTML/CSS   | Frontend |
| Bootstrap  | Styling |
| Python     | Core Logic |

---

| Name                   | Description                               |
| ---------------------- | ----------------------------------------- |
| `e-commerce-Django/`   | Root project directory                    |
| ├── `ecommerce/`       | Django project settings and configuration |
| ├── `cart/`            | Django app: views, models, URLs, logic    |
| ├── `templates/cart/`  | HTML templates for frontend rendering     |
| ├── `media/products/`  | Uploaded product images                   |
| ├── `db.sqlite3`       | Default SQLite database                   |
| ├── `Dockerfile`       | Docker configuration (optional)           |
| ├── `manage.py`        | Django project management script          |
| └── `requirements.txt` | Python dependencies file                  |


---

## ⚙️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/madhill41422/e-commerce-Django-main.git
   cd e-commerce-Django

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate     # For Linux/macOS
   venv\Scripts\activate        # For Windows

---

3. Install dependencies:
   ```bash
   pip install -r requirements.txt


4. Run database migrations:
   ```bash
   python manage.py migrate


5. Start the development server:
   ```bash
   python manage.py runserver




---

🛠️ Admin Credentials

To access the admin panel:

      python manage.py createsuperuser

# Enter your username, email, and password when prompted

Then go to http://127.0.0.1:8000/admin/ to log in.

---

🌐 Optional Deployment

This project can be deployed on:

AWS or azure 

Want a deployment guide? Just raise an issue or contact me!


---

🙋‍♂️ About Me

I'm Madhusudhan Reddy, an aspiring DevOps & Cloud Engineer who loves building real-world projects.

🔗 https://www.linkedin.com/in/madhusudhan-reddy-8143a5234

📧 madhusudhanreddy9740@gmail.com



---

⭐ Support

If you find this project helpful, don't forget to star 🌟 the repository!

---
