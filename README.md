LaundryFlow – Smart Laundry Management System
Project Overview

LaundryFlow is a web-based Smart Laundry Management System designed to streamline laundry service operations in a hostel or university environment. The system provides separate interfaces for students and administrators, enabling efficient order placement, complaint handling, feedback collection, and detergent stock management.

This project is built using front-end technologies (HTML, CSS, and JavaScript) and runs entirely in the browser without requiring a backend server.

Objectives

To simplify the process of placing laundry orders for students.

To provide administrators with tools to manage orders and stock efficiently.

To maintain transparency in order status tracking.

To digitally manage complaints and feedback.

To simulate real-time stock deduction for detergents.

Features
1. Student Module

Student login interface

Place laundry orders

Select wash type (Gentle, Daily, Hard)

Choose detergent type (Ariel, Tide, Surf Excel)

View order status (Pending, Processing, Completed)

File complaints

Submit feedback

2. Admin Module

Admin login interface

View all laundry orders

View complaints submitted by students

View student feedback

Monitor detergent stock levels

Manage stock (increase/decrease inventory)

3. Stock Management

Real-time detergent stock display

Automatic stock reduction when an order is placed

Low stock indication

Admin-controlled stock updates

Technology Stack

HTML5

CSS3

JavaScript (Vanilla JS)

No external frameworks or backend technologies are used.

System Architecture

This project follows a client-side architecture:

HTML for structure

CSS for styling and layout

JavaScript for logic, data handling, and page navigation

Data is stored temporarily in JavaScript arrays (in-memory storage)

Since there is no database integration, all data resets when the page is refreshed.

How to Run the Project

Download or clone the repository.

Open the project folder.

Open index.html in any modern web browser (Chrome, Edge, Firefox).

The system will load directly in the browser.

No server setup is required.

Default Behavior

Login is simulated (no real authentication).

Sample orders, complaints, and feedback are preloaded.

All operations are handled dynamically using JavaScript.

Limitations

No real authentication system.

No database connectivity.

Data is not persistent after page refresh.

No role-based security validation.

Designed only for demonstration or academic purposes.

Future Enhancements

Integration with a backend (Node.js / PHP / Django)

Database support (MySQL / MongoDB)

Real authentication with encrypted passwords

Order filtering and sorting options

SMS or email notifications

Payment gateway integration

Mobile responsive optimization

Use Case

This system is suitable for:

University hostel laundry management

Small-scale laundry businesses

Academic demonstrations of web application design

Software Development and Design coursework projects

Author

Project developed as part of academic coursework in Software Engineering.
