📖 Overview

This project is a Python-based payroll automation system that generates employee payslips from a payroll dataset, converts them to PDF, and automatically emails them to employees.

The system eliminates manual HR work by automating:

1. Payslip generation
2. PDF conversion
3. Email distribution
4. Email delivery logging

It is designed for small to medium-sized organizations that manage payroll using Excel.

🚀 Features

✔ Automated payslip generation from Excel template
✔ Automatic PDF conversion of payslips
✔ Bulk email delivery to employees
✔ Support for multiple employee email addresses
✔ Ability to CC HR or finance departments
✔ Email logging system for monitoring sent/failed emails
✔ Efficient processing by opening Excel only once

🛠 Technologies Used

  Python
  Pandas – Data processing
  OpenPyXL – Excel manipulation
  Win32com – Excel automation
  SMTP (Gmail) – Email delivery
  EmailMessage – Email creation

📂 Project Structure

project
│
├── data
│   └── payroll.csv
│
├── templates
│   └── payslip_template.xlsx
│
├── output
│   ├── excel
│   └── pdf
│
├── logs
│   └── email_log.csv
│
└── payroll_system.py


⚙️ Setup Instructions

1️⃣ Install Required Libraries
pip install pandas openpyxl pywin32

2️⃣ Enable Gmail App Password
To send emails using Gmail SMTP:

Enable 2-Step Verification
Generate an App Password
Use the generated password in the script

3️⃣ Configure Email Credentials

Edit the script:
sender_email = "yourcompany@gmail.com"
password = "your_app_password"

4️⃣ Run the Script
python payroll_system.py

The system will:

Generate payslips
Convert them to PDF
Send emails
Record results in the log file

🔒 Security Considerations
Use App Passwords instead of your Gmail password
Protect payroll data securely
Avoid storing sensitive credentials in public repositories

📈 Future Improvements

Possible enhancements include:

Payroll dashboard
Employee payslip portal
Web-based interface
Cloud storage for payslip history
Retry mechanism for failed emails
API integration with HR systems

👨‍💻 Author

Iroanya David

Data Analyst | Automation Developer
