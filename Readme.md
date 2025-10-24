# 🏥 Hospital Management System  

**Duration:** Dec 2023 – Feb 2024  
**Tech Stack:** Python, Django, HTML, CSS, JavaScript, SQLite, Bootstrap  

---

## 📖 Overview  

The **Hospital Management System** is a role-based web application designed to simplify hospital operations through distinct modules for **Admin**, **Doctor**, and **Patient**.  
It enables appointment booking, patient discharge workflows, and automated bill generation with downloadable receipts.  

---

## ⚙️ Features  

- 👨‍⚕️ **Admin Module** – Manage doctors, patients, and appointments.  
- 🧾 **Doctor Module** – View assigned patients and update treatment records.  
- 🧍 **Patient Module** – Register, book appointments, and download receipts.  
- 💰 **Billing System** – Generate and download PDF invoices for discharge.  
- 🔐 **Authentication** – Secure, role-based login system for each user type.  

---

## 🛠️ Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/hospital-management-system.git
cd hospital-management-system
2️⃣ Create a Virtual Environment
bash
Copy code
python -m venv venv
3️⃣ Activate the Virtual Environment
Windows:

bash
Copy code
venv\Scripts\activate
macOS/Linux:

bash
Copy code
source venv/bin/activate
4️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
5️⃣ Run Database Migrations
bash
Copy code
python manage.py makemigrations
python manage.py migrate
6️⃣ Start the Development Server
bash
Copy code
python manage.py runserver

🧰 Project Structure
csharp
Copy code
hospital-management-system/
│
├── hospital/                # Main Django app
├── templates/               # HTML templates
├── static/                  # CSS, JS, and Bootstrap assets
├── db.sqlite3               # SQLite database
├── manage.py
├── requirements.txt
└── README.md
📈 Future Improvements
📬 Email/SMS notification system for appointment updates

📊 Analytics dashboard for hospital statistics

🗃️ Switch to PostgreSQL for improved scalability

🧑‍💼 Enhanced admin reports and filtering options

👨‍💻 Author
Sakthivel S
Full Stack Developer – Python