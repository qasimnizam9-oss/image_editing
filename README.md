EditingMonkey
A Full-Stack Image Processing & Conversion Suite

EditingMonkey is a powerful Flask-based web application that allows users to upload images and convert them into various professional formats like PDF, Word, and Excel, or apply edits like Grayscale. It features a secure authentication system backed by a MySQL database.

🚀 Features
Secure Authentication: User signup and login with PBKDF2 password hashing.

Image Editing: Convert images to Grayscale or handle modern formats like JFIF.

Document Conversion: * Image to PDF: High-quality conversion using img2pdf.

Image to Word: Insert images into .docx files automatically.

Data Extraction: Export image metadata (dimensions and filename) to Excel or CSV.

Contact System: Integrated contact form that saves messages directly to MySQL.

🛠️ Tech Stack
Backend: Python / Flask

Database: MySQL (via SQLAlchemy)

Libraries: Pillow (Image processing), Pandas (Data handling), python-docx (Word), img2pdf (PDF).
