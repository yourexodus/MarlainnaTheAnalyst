# 🏪 Flask Store API

A fully functional **RESTful API** built with **Flask-Smorest** to manage store inventory, including items, stores, tags, and users.  
This project demonstrates best practices in API design, modular architecture, and Docker-based deployment — built while balancing full-time work and motherhood 💪🏽.

---

## 🚀 Features

- 🔹 CRUD operations for **Users**, **Stores**, **Items**, and **Tags**  
- 🔹 RESTful routing with parameterized endpoints  
- 🔹 Input validation and robust error handling (404, 400)  
- 🔹 Modular architecture using **Blueprints** and **MethodViews**  
- 🔹 Auto-generated API documentation with **Swagger UI**  
- 🔹 JWT-based authentication for secure access  
- 🔹 Dockerized for scalable deployment  

---

## 🛠️ Tech Stack

| Category | Tools |
|-----------|--------|
| **Language** | Python |
| **Framework** | Flask, Flask-Smorest |
| **Auth & Security** | Flask-JWT-Extended |
| **Testing / Docs** | Postman, Swagger UI |
| **Deployment** | Docker |
| **Version Control** | Git & GitHub |

---

## 🧩 Project Structure

| Folder | Description |
|---------|-------------|
| [`/models`](https://github.com/yourexodus/mfrancis_restAPI/tree/main/models) | SQLAlchemy database models |
| [`/resources`](https://github.com/yourexodus/mfrancis_restAPI/tree/main/resources) | API Blueprints (User, Store, Item, Tag) |
| [`app.py`](https://github.com/yourexodus/mfrancis_restAPI/blob/main/app.py) | Flask application entry point |
| [`db.py`](https://github.com/yourexodus/mfrancis_restAPI/blob/main/db.py) | Database initialization |
| [`blocklist.py`](https://github.com/yourexodus/mfrancis_restAPI/blob/main/blocklist.py) | JWT token blocklist |
| [`schemas.py`](https://github.com/yourexodus/mfrancis_restAPI/blob/main/schemas.py) | Marshmallow schemas for data validation |
| [`requirements.txt`](https://github.com/yourexodus/mfrancis_restAPI/blob/main/requirements.txt) | Dependencies list |
| [`Dockerfile`](https://github.com/yourexodus/mfrancis_restAPI/blob/main/Dockerfile) | Docker container configuration |

---

## 🧠 User Flow (Authentication & Authorization)

![User Flowchart](https://github.com/yourexodus/mfrancis_restAPI/raw/main/docs/user_flowchart.png)

> This flowchart illustrates the **User Authentication Process**, including registration, login, token creation, and JWT validation.

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourexodus/mfrancis_restAPI.git
   cd mfrancis_restAPI
