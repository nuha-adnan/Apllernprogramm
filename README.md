Lernprogramm

This project is a web-based learning application that provides users with an interactive platform to study various subjects, answer questions, and track their learning progress. The application is built using HTML, CSS, and JavaScript and includes features for rendering mathematical expressions, offline access, and more.
Project Overview
File Structure

    index.html: The main HTML file that structures the application and links all necessary resources.
    ./src/style.css: The CSS file that styles the interface, including layout, typography, and interactive elements.
    ./src/script.js: The JavaScript file responsible for managing the application’s functionality, such as tab navigation, question display, and progress tracking.
    ./src/icon.png: The icon file used as the favicon for the application.
    ./manifest.json: The web app manifest file that defines the application's appearance and behavior when installed on a user's device.

Dependencies

    KaTeX: A library used to render mathematical expressions in LaTeX format, allowing for complex math questions to be displayed properly.
    Service Worker: A script that enables the application to function offline and improves loading performance by caching key resources.

Features

    Subject Tabs: The application includes multiple subjects (Mathematik, Internettechnologien, Allgemeines Wissen, and Externaufgaben), each accessible via tab navigation.
    Question Display: Each subject has its own set of questions with multiple-choice options, displayed dynamically as users interact with the app.
    Progress Tracking: A progress bar shows the user's advancement through the questions, giving real-time feedback on learning progress.
    Statistics: A dedicated section for viewing the user's score and an option to reset progress.
    Offline Access: The application is designed to work offline, thanks to the service worker and manifest setup.

Getting Started

To run this project locally:

    Clone the repository:

    bash

git clone https://github.com/yourusername/lernprogramm.git

Navigate to the project directory:

bash

    cd lernprogramm

    Open index.html in your web browser to start using the application.

Future Enhancements

    Additional Subjects and Questions: Expand the range of subjects and increase the number of questions for a more comprehensive learning experience.
    User Profiles: Implement user authentication to save progress and personalize the learning experience across sessions.
    Improved UI/UX: Enhance the user interface and experience for better accessibility and engagement.
    Backend Integration: Develop a backend system to store user data, track long-term progress, and offer more advanced features.

License

This project is licensed under the MIT License. Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request
