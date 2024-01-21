# Yoga_Classes_Web_Page

## Project Description
### Overview
This web application facilitates the booking of yoga classes, offering users a seamless experience to create accounts, log in securely, view available classes, and book their preferred sessions. The system also includes an admin section for efficient management and monitoring of user payments.

### Key Features
1. User Authentication:
    * Users can securely create accounts and log in using their email addresses and passwords.
2. Class Booking:
   * View a list of available yoga classes.
   * Check class details, including class name, schedule, and instructor information.
   * Book classes of their choice.
   * Receive payment information upon successful booking.
   * Update the class status after booking.
3. Admin Dashboard:
   * Admin users can access a dedicated admin page for effective monitoring and management of user payments.
   * The admin dashboard displays key details such as username, class name, price before tax, total amount paid, and the date of payment.
4. Session Management:
   * The application employs Express.js and express-session for session management, keeping track of user login status and distinguishing between regular users and administrators.
5. Database Integration:
   * MongoDB serves as the database to store essential information, including user details, class information, and payment records.
6. Handlebars Templating:
   * The application uses the Handlebars template engine to render dynamic HTML pages, ensuring a consistent layout and user experience.
7. Responsive Design:
   * The front-end features a simple and responsive design, making the application accessible across various devices.
8. CSS Styling:
   * The included stylesheet (styles.css) enhances the visual appeal of the user interface, providing a polished and user-friendly experience.

## Instructions
1. System Requirements: Ensure Node.js and MongoDB are installed on your machine.
2. Installation: Run npm install to install project dependencies.
3. Database Configuration: Set up a MongoDB Atlas account and replace the connection string in the code with your own.
4. Run the Application: Execute npm start to launch the application.
5. Access: Open a web browser and navigate to http://localhost:8080 to access the application.a
