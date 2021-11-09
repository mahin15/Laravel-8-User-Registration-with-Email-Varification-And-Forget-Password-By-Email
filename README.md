Project Brief
Hello Every One !
This is A Basic Laravel E-Commerce Web Project with Functional Admin Panel
In This Project We Are Using Laravel 8
In This Project We Are Shown Register User With Email Verification & Forget Password Process also With in Email
Now Check All Steps 

1) For Email Varification first, We Have to Make SMTP Mail Server Local

2) We Can Use Our Own Gmail Account For Doing This

3) First Go to "Manage Your Google Account"

4) Select "Security" on Left Side

5) Scroll Down And Select App Password

6) "Select the app and device you want to generate the app password for."
Select "Mail" For App
Select "Windows Computer" For Device
The Click on "Generate"

7) You Can Get A Password For SMTP Mail Server

8) Now got to ".env" file and update few on below points
..........................................................
MAIL_MAILER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=your mail id
MAIL_PASSWORD=password which you getting from "App Password"
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS=your mail id
MAIL_FROM_NAME="${APP_NAME}"
............................................................

rest of others don't need to change

Now here's the Register User With Email Verification & Forget Password Process also With in Email



Build Status Total Downloads Latest Stable Version License

About Laravel
Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

Simple, fast routing engine.
Powerful dependency injection container.
Multiple back-ends for session and cache storage.
Expressive, intuitive database ORM.
Database agnostic schema migrations.
Robust background job processing.
Real-time event broadcasting.
Laravel is accessible, powerful, and provides tools required for large, robust applications.

Contributing
Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the Laravel documentation.

Code of Conduct
In order to ensure that the Laravel community is welcoming to all, please review and abide by the Code of Conduct.

Security Vulnerabilities
If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via taylor@laravel.com. All security vulnerabilities will be promptly addressed.

License
The Laravel framework is open-sourced software licensed under the MIT license.

Laravel-8-Basic-E-Commerce-Product-ADD-EDIT-DELETE-SHOW
