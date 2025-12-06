# Shot & Asset Tracker API

This is a personal capstone project that combines my experience in the VFX industry with backend development skills. The goal is to build a robust production tracking API inspired by tools like Shotgun, ftrack, and Jira—focusing specifically on shot and asset management for visual effects (VFX) pipelines.

Through this project, I aim to deepen my understanding of backend architecture, API development, deployment practices, and software engineering workflows.

## 🛠 Tech Stack

- **Backend Framework:** Django + Django REST Framework
- **Database:** PostgreSQL
- **Authentication:** Token-based (with role-based access control)
- **DevOps & Deployment:** Git, Jenkins (CI for tests/linting), AWS EC2 + RDS (for production)
- **Extras:** Redis (optional), Webhooks (for payments), Pagination, Search, Caching

## 🎯 Project Goals

- Apply real-world backend skills in a structured project.
- Demonstrate production-ready API design with auth, role management, and performance optimizations.
- Deploy a full Django backend to AWS with production settings.

## 📦 What It Tracks

- **Shows** → **Sequences** → **Shots**
- **Assets** (models, rigs, FX setups, etc.)
- **Tasks** (assigned to users and roles)
- **Statuses** (e.g., Todo, WIP, Review, Approved, On Hold)
- **Deadlines & Scheduling**
- **Review Notes / Feedback Threads**
- *(Optional)*: Payments / Invoices for vendors or premium users

## 👤 User Roles

- **Admin**
- **Producer**
- **Supervisor**
- **Artist**
- **Client (Read-only)**

## 🚧 Work in Progress

This project is still under development and intended primarily for learning purposes. Contributions or suggestions are welcome!

## Local Deployment

1. **Create a virtual environment:**

   ```bash
   python -m venv venv
   ```
2. **Activate the virtual environment:**

   ```bash
   venv\Scripts\activate
   ```
3. **Install required packages:**

   ```bash
   pip install -r requirements.txt
   ```
4. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

> The server should now be accessible at http://127.0.0.1:8000/.
