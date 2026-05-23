# Student Management System
A JavaFX desktop application for managing student information with user authentication and database integration.
This project was initially based on the workshop starter repository provided by the facilitator and was further customized and extended for the activity requirements.

## Features
- User Login and Registration (Sign Up)
- Secure password hashing (SHA-256)
- Database connection using Supabase (PostgreSQL)
- Student data management (Add, Update, Delete, Clear)
- Pagination for viewing student records
- PUP themed JavaFX user interface

## Technologies Used
- Java (JDK 21)
- JavaFX
- Maven
- PostgreSQL (Supabase)
- Dotenv for environment variables (security)

## Database
This project uses **Supabase** as the database.

Tables included:
- `users` – for authentication
- `students` – for student records
