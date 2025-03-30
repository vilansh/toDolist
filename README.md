# Todo List Handler (Express.js)

## Overview
This is a simple and efficient **Todo List Handler** built with **Node.js** and **Express.js**. It allows users to create, manage, and organize their daily tasks efficiently with an intuitive and dynamic user interface.

## Features
- **Home Page:** Displays all created tasks/posts.
- **Create Task/Post:** Users can add new tasks via a simple form.
- **Dynamic Routing:** Each task can be accessed through its unique URL.
- **About & Contact Pages:** Informative pages for additional project context.
- **Minimalistic UI:** Built using **EJS templating engine** for clean and structured rendering.
- **Static File Handling:** Public assets like CSS and JS are served statically.

## Tech Stack
- **Backend:** Node.js, Express.js
- **Frontend:** EJS (Embedded JavaScript Templates)
- **Middleware:** body-parser
- **Utilities:** lodash (for case-insensitive URL handling)

## Installation

### Prerequisites
Ensure you have **Node.js** installed on your machine.

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/todo-list-handler.git
   cd todo-list-handler
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the application:
   ```sh
   npm start
   ```

4. Open your browser and navigate to:
   ```sh
   http://localhost:3000
   ```

## Project Structure
```
├── public          # Static files (CSS, JavaScript, Images)
├── views          # EJS Templates
│   ├── home.ejs
│   ├── about.ejs
│   ├── contact.ejs
│   ├── compose.ejs
├── app.js         # Main Express server file
├── package.json   # Project metadata and dependencies
└── README.md      # Project documentation
```

## API Endpoints
### GET Endpoints
- `/` → Renders the homepage with task listings
- `/about` → Displays the About page
- `/contact` → Displays the Contact page
- `/compose` → Renders a form to create a new task

### POST Endpoints
- `/compose` → Saves new tasks and redirects to home

## Future Enhancements
- **Database Integration:** Store tasks persistently using MongoDB/MySQL
- **Authentication:** User login system for personalized task management
- **Task Status Update:** Mark tasks as completed
- **Deployment:** Host on platforms like Heroku/Vercel for live access

## License
This project is licensed under the **MIT License**.

## Author
Developed by Vilansh. Feel free to contribute or report issues!

---
_If you find this project helpful, give it a ⭐ on GitHub!_

