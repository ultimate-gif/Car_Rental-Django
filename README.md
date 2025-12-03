Car Rental System — Django Based Web Application

A full-stack Django-based Car Rental Management System that allows customers to browse available cars, book rentals, manage their bookings, and interact with car dealers.
The system includes separate modules for customers, car dealers, and admin, providing a complete workflow for managing car rental operations.

📌 Features
👤 Customer Portal

User registration & login

Browse available cars

View car details

Submit rental requests

Manage bookings

Profile management

🚘 Car Dealer Portal

Add/update car listings

Manage availability

View rental requests from customers

Approve or reject bookings

🛠 Administrator

Full system control

Manage customers & dealers

Approve dealer registrations

View overall rental reports

🧱 Project Structure
Car_Rental-Django/
│
├── car_dealer_portal/     # Dealer features and dashboards
├── customer_portal/       # Customer-facing features
├── home/                  # Landing pages and global templates
├── ocrs/                  # Main Django project settings
├── static/                # CSS, JS, images, front-end assets
│
├── manage.py              # Django management script
└── README.md              # Project documentation

🛠 Tech Stack
Component	Technology
Backend	Django (Python)
Frontend	HTML, CSS, Bootstrap
Database	SQLite / MySQL
Templates	Django Templates
Architecture	MVT (Model-View-Template)
🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/ultimate-gif/Car_Rental-Django.git
cd Car_Rental-Django

2️⃣ Create a virtual environment
python -m venv venv
venv\Scripts\activate   # Windows

3️⃣ Install dependencies
pip install -r requirements.txt


(If requirements.txt is missing, I can help you generate one.)

4️⃣ Apply migrations
python manage.py migrate

5️⃣ Run the server
python manage.py runserver


Now open your browser and visit:

http://127.0.0.1:8000/

📷 Screenshots (optional — I can help add)

You can upload screenshots of:

Home page

Customer dashboard

Dealer dashboard

Booking page

I can format them nicely in the README.

📄 Project Information Files

Your repository already includes:

01 PROJECT INFO.txt – project explanation

Car Rental System2.pptx – presentation slides

If you want, I can extract the content from them and improve the README further.

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to improve.

📜 License

You can add a license (MIT recommended).
Tell me if you want me to add it.