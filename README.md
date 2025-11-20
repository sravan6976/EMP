📧 EMP – Employee Mail Portal

A JSP/Servlet-based web application that allows employees to securely log in, change their default password, and send messages to HR. This project demonstrates full-stack development using Java, JSP, Servlets, JDBC, MySQL, frontend styling, sessions, and SMTP integration.

🚀 Features
🔐 Authentication & Security

Employee login using UserID + Password

Identifies whether user is using default password

Forces employee to change password on first login

Passwords stored securely in database

💬 Employee → HR Messaging

Dedicated message page for employees

Messages are stored in the database

HR receives the message through email via Gmail SMTP

Auto-includes employee email & code in the message

🎨 Responsive & Modern UI

Stylish glassmorphism UI

Blue branded background

Company logo integrated

Polished JSP pages:

login.jsp

changePassword.jsp

message.jsp

🗄️ Database

Uses MySQL / Oracle XE

Tables:

employees → Stores employee credentials & info

messages → Stores employee messages sent to HR

📨 Email Integration

Uses JavaMail (SMTP)

Sends HR an email with:

Employee code

Employee email

Employee’s message
