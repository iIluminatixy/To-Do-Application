# ✦ GlassTask: A Visually Stunning To-Do & Reminders App

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

GlassTask is a beautifully designed, modern To-Do and Reminders application with a unique 'liquid glass' aesthetic. Built with HTML, CSS, and JavaScript, it offers a visually appealing interface with smooth animations and a glassy UI effect. The application allows users to manage tasks, set due dates and times, assign priorities and categories, and even set reminders. It leverages `localStorage` for data persistence, making it a functional, client-side application.

## Table of Contents

- [Project Title & Badges](#project-title--badges)
- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Important Links](#important-links)
- [Footer](#footer)

## Features ✨

- **Liquid Glass UI:** A modern and visually engaging interface with blurred, translucent elements and animated backgrounds.
- **Task Management:** Add, edit, mark as complete, and delete tasks with ease.
- **Due Dates & Times:** Schedule tasks with specific due dates and times.
- **Prioritization:** Assign High, Medium, or Low priority to tasks.
- **Categorization:** Organize tasks into categories like Work, Personal, Health, and Study.
- **Reminders:** Set custom reminders for tasks (e.g., 5 minutes before, 1 hour before).
- **Search & Filtering:** Quickly find tasks by keyword and filter by status (All, Pending, Done) or category.
- **Sorting:** Sort tasks by creation date, due date, or priority.
- **Progress Tracking:** Visual progress bar showing the completion rate of tasks.
- **Notifications:** Browser notifications for task reminders.
- **Responsive Design:** Adapts to different screen sizes.
- **Local Storage Persistence:** Tasks are saved locally in the browser.
- **Keyboard Shortcuts:** For quick access to modal and closing.

## Tech Stack 🛠️

- **HTML:** For structuring the web page.
- **CSS:** For styling, including custom animations, gradients, and the signature 'liquid glass' effect.
- **JavaScript:** For all application logic, DOM manipulation, local storage, and user interactions.
- **Tailwind CSS (via CDN):** Used for utility-first CSS classes to rapidly build the UI (`https://www.gstatic.com/antigravity/web/dev/tailwindcss.min.js`).

## Installation 🚀

This is a client-side application and does not require a complex installation process. You can use it directly by opening the `index.html` file in your web browser.

**Steps:**

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/iIluminatixy/To-Do-Application.git
    ```
2.  **Navigate to the Project Directory:**
    ```bash
    cd To-Do-Application
    ```
3.  **Open `index.html`:**
    Open the `index.html` file in your preferred web browser.

*No backend, build tools, or external dependencies are required, making it incredibly easy to run.* 

## Usage 💡

GlassTask is designed for simple and intuitive task management. All functionalities are accessible directly from the main interface.

### Core Functionality:

-   **Adding Tasks:** Click the `New Task` button in the header to open the modal. Fill in the task details (title is mandatory) and click `Add Task`.
-   **Editing Tasks:** Click the edit icon (pencil) on an existing task to modify its details.
-   **Completing Tasks:** Click the circular checkbox next to a task to mark it as done. Click again to unmark.
-   **Deleting Tasks:** Click the delete icon (trash can) next to a task to remove it permanently.
-   **Searching:** Use the search bar to filter tasks by keywords in their title or description.
-   **Filtering:** Use the `All`, `Pending`, `Done` buttons to filter the visible tasks.
-   **Sorting:** Use the dropdown menu to sort tasks by creation date, due date, or priority.
-   **Categorizing:** Use the category buttons to filter tasks by their assigned category.
-   **Viewing Stats:** The header displays key statistics like Total, Completed, and Pending tasks, along with today's progress.
-   **Reminders:** When adding or editing a task, you can set a reminder that will trigger a browser notification and a toast message.

### Example Workflow:

1.  Open `index.html` in your browser.
2.  Click `New Task`.
3.  Enter `Buy groceries` as the title.
4.  Select `Personal` as the category and `High` priority.
5.  Set a due date for tomorrow.
6.  Set a reminder for 1 hour before.
7.  Click `Add Task`.
8.  The task appears in your list. Click the checkbox to mark it as done when finished.

## How to Use 🖥️

GlassTask is a self-contained, client-side web application. You can use it offline directly from your browser. The interface is designed to be intuitive:

1.  **Access:** Simply open the `index.html` file in any modern web browser.
2.  **Interaction:** Use the `New Task` button to add items, checkboxes to mark completion, and the search/filter options to manage your list.
3.  **Data Storage:** All your tasks are saved in your browser's local storage. They will persist even after you close the tab or browser.
4.  **Reminders:** For reminders to function, you may need to grant browser notification permissions when prompted.

This application is ideal for personal task management, quick to-do lists, and simple reminder needs without requiring any server setup.

## Project Structure 📁

```
/
├── index.html
└── README.md
```

-   **`index.html`**: Contains all the HTML structure, CSS styles (embedded), and JavaScript logic for the application.
-   **`README.md`**: This documentation file.

## Contributing 🤝

Contributions are welcome! Since this is a personal project, please feel free to:

-   Fork the repository.
-   Create a new branch (`git checkout -b feature/YourFeature`).
-   Make your changes.
-   Commit your changes (`git commit -m 'Add some YourFeature'`).
-   Push to the branch (`git push origin feature/YourFeature`).
-   Open a Pull Request.

Please ensure your code is clean and follows the existing style. For major changes, please open an issue first to discuss what you would like to change.

## License 📜

This project is licensed under the **MIT License**. See the `LICENSE` file for more details (if available, otherwise assume MIT).

## Important Links 🔗

-   **GitHub Repository:** [https://github.com/iIluminatixy/To-Do-Application](https://github.com/iIluminatixy/To-Do-Application)
-   **Live Demo:** (No live demo link provided, but can be hosted easily on platforms like GitHub Pages or Netlify by simply deploying the `index.html` file).

## Footer 📝

This project was developed by [iIluminatixy](https://github.com/iIluminatixy).

-   **Repository:** [To-Do-Application](https://github.com/iIluminatixy/To-Do-Application)
-   **Author:** [iIluminatixy](https://github.com/iIluminatixy)
-   **Contact:** (Contact information not provided)

--- 

We hope you enjoy using GlassTask! Feel free to:

⭐ Star this repository

👁️ Watch for updates

🔔 Open an issue if you find a bug or have a suggestion

<div align="center">
  Made with ❤️ and JavaScript
</div>
