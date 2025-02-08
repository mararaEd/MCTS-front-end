# MCTS-front-end

## Description

This is a Meal Card System front-end application designed to manage and verify meal access for students and staff. It provides an interface for administrators to manage users and generate reports, and for staff to verify meal access using QR codes or manual ID input. Students can view their profile and QR code.

## Technologies Used

*   Vite
*   Sass
*   Chart.js
*   html5-qrcode

## Installation and Running

1.  Clone the repository:

    ```bash
    # Assuming you have the files already
    # git clone <repository-url>
    # cd MCTS-front-end
    ```

2.  Install the dependencies:

    ```bash
    npm install
    ```

3.  Run the application:

    ```bash
    npm run dev
    ```

    This will start the development server.

## Project Structure

*   `index.html`: Main HTML file.
*   `main.js`: Main JavaScript file that initializes the application.
*   `style.css`: Main CSS file.
*   `styles/`: Contains Sass files.
*   `js/`: Contains JavaScript modules for different parts of the application:
    *   `auth.js`: Handles authentication logic.
    *   `router.js`: Handles routing and navigation.
    *   `pages/`: Contains modules for different pages:
        *   `login.js`: Login page.
        *   `dashboard.js`: Dashboard page for admins and students.
        *   `profile.js`: Profile page.
        *   `staff.js`: Staff verification page.
*   `public/`: Contains static assets such as images.
