# SD-3101 Canteen Management System: Optimizing Food Ordering and Inventory Management with PHP and MySQL

![2e22ae0e-1549-48c6-806e-578a7fc99433](https://github.com/user-attachments/assets/73e65c78-67b6-4665-bd22-d9852d8df4a9)

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage Instructions](#usage-instructions)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [Chagelog](#changelog)
- [Acknowledgments](#acknowledgments)
- [License](#license)

---

## Introduction
The Canteen Management System (CMS) is a web-based application designed to streamline the process of food ordering and management within an educational institution's canteen. Developed as a project for the CS213 SSL course, CMS offers a user-friendly interface for both customers and canteen owners to interact with.

## Project Overview
### Project Background
Managing canteens in schools, offices, and public spaces often involves inefficient manual processes. A Canteen Management System digitizes operations like order processing, inventory control, and cashless transactions, enhancing speed and accuracy while reducing errors and food waste.

### Target Audience
- Students & Staff: 
Quick, mobile-friendly ordering in educational institutions.
- Corporate Employees: 
Pre-order and digital payment options for faster breaks.
- Canteen Managers: 
Automated inventory and financial tracking for improved efficiency.

### Real-World Applications
- Faster Service: 
Reduces wait times with digital ordering and payment options.
- Cashless Transactions:
Supports mobile payments and improves financial transparency.
-  Inventory Management: 
Tracks stock and reduces food wastage.
- Pre-ordering: 
Allows customization and pre-ordering of meals.
Potential Impact

## Objectives
- Develop a solution for inefficient manual canteen processes, such as order-taking, billing, and inventory management, by creating a streamlined digital platform.

- Implement features to enhance service efficiency, including mobile ordering, real-time menu updates, cashless payments, and automated inventory tracking to reduce delays and errors.

- Test and validate the system’s performance, ensuring smooth order processing, reliable transaction handling, and accurate inventory control in real-world canteen environments.

## Features
List the main features of the project:
### For Customers
-Feature 1:  **Login and Registration:** New users can register, while existing users can login with their credentials.
-Feature 2: **View Menu:** Customers can view the canteen menu along with item details such as name, price, and type (Veg/Non-veg).
-Feature 3: **Place Orders:** Customers can add desired items to their cart and specify the quantity.
-Feature 4:**Payment Options:** Customers can choose to pay via UPI or cash.

### For Canteen Owners
-Feature 5: **Menu Management:** Owners can modify the menu and change the availability status of items.
-Feature 6: **Order Management:** Owners can view details of all orders placed and check payment statuses.

## Technologies Used
Mention the tools, frameworks, and technologies used in the project:
- Programming Languages: PHP
- Databases: MySQL
- Other Tools:XAMMP

## Setup and Installation
Step-by-step instructions for setting up the project locally.

1. **Start XAMPP:** Start the XAMPP control panel and ensure that both Apache and MySQL services are running.

2. **Clone the repository:** Clone the project repository to your local machine.

3. **Move files to XAMPP's htdocs directory:**
   - Copy the entire cloned repository folder and paste it into the `htdocs` directory in your XAMPP installation folder.

4. **Database Initialization:**
   - Open your web browser and navigate to `http://localhost/canteen-management-system/init/init.php`. This will initialize the database and set up necessary tables.

5. **Access the application:** After the database initialization is complete, navigate to `http://localhost/canteen-management-system/home/home.php` in your web browser.

6. **Usage:** Once the home page is loaded, you can register/login as a customer or access the canteen owner portal to manage the menu and view orders.


## Usage Instructions
- **Admin**: The admin has a complete control to the system.
- **Customer** : The customer can order food.

## Project Structure
Explain the structure of the project directory. Example:
```bash
.
└── canteen management system/
    ├── css/
    │   ├── style.css
    │   ├── style1.css
    │   ├── style2.css
    │   ├── style3.css
    │   ├── style4.css
    │   ├── style5.css
    │   ├── style6.css
    │   └── style7.css
    ├── home/
    │   ├── home.php
    │   ├── login_admin.php
    │   ├── login.php
    │   ├── register_admin.php
    │   └── register.php
    ├── init/
    │   ├── init.php
    │   ├── mysqlsampledatabase.sql
    │   └── outit.php
    ├── php/
    │   ├── add_item.php
    │   ├── added_item.php
    │   ├── change_item.php
    │   ├── changed_item.php
    │   ├── delete.php
    │   ├── deleted.php
    │   ├── deliver.php
    │   ├── delivered.php
    │   ├── edit.php
    │   ├── edited.php
    │   ├── main_admin.php
    │   ├── main.php
    │   ├── order.php
    │   ├── pay.php
    │   └── payyed.php
    └── README.md
```

## Contributors

List all the team members involved in the project. Include their roles and responsibilities:

- **Lily Anne Vitangcol**: Lead Developer, Backend Developer
- **Christina Ardeza**: Frontend Developer, UI/UX Designer
- **Gerald Villaran**: Project Manager, Tester

## Project Timeline

Outline the project timeline, including milestones or deliverables. Example:

- **Week 1-2**: Collaborative Brainstorming for Feature Development
- 09/16/2024
- Meeting Recording: https://youtu.be/MGo5k7BQodU
- Proposes Features
1. Separate Logins for Admin and Users
2. Multiple Room Bookings
3. Guest Reviews and Ratings
4. Booking Summary Page
5. Special Offers and Promos
6. Booking Confirmation
7. Calendar Booking View
8. Customizable Stay Reminders
9. Room Preference Notes
10. Cancellation and Modification Options

   - Feature: Dockerize Project
   - Target Completion: 27/10/2024

- **Week 3-5**: Design and setup.
- **Week 6-10**: Implementation.
- **Week 11-12**: Testing and debugging.
- **Week 13-14**: Final presentation and documentation.

## Changelog

### [Version 1.0.0] - 2024-09-07
- Initial release of the project.
- Added basic functionality for [Feature 1], [Feature 2], and [Feature 3].

### [Version 1.1.0] - 2024-09-14
- Improved user interface for [Feature 1].
- Fixed bugs related to [Feature 2].
- Updated project documentation with setup instructions.

### [Version 1.2.0] - 2024-09-21
- Added new functionality for [Feature 4].
- Refactored codebase for better performance.
- Added unit tests for [Feature 3] and [Feature 4].


## Acknowledgments

Acknowledge any resources, mentors, or external tools that helped in completing the project.

This project was built from (https://github.com/SanchiSujithKumar/Canteen-Management-System?tab=readme-ov-file), created by SanchiSujithKumar
. You can view the original repository [here](https://github.com/username/original-repo).

## License

Specify the project's license. For starters, adapt the license of the original repository.
"# se2024-ardeza-vitangcol" 
"# se2024-ardeza-vitangcol" 
"# se2024-ardeza-vitangcol" 
"# se2024-ardeza-vitangcol" 
