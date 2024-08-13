# Note Taker Starter Code


## Description

The **Note Taker** application is a simple tool for writing and saving notes. Built with Express.js on the backend, this app allows users to easily create, view, and manage their notes. The application includes a front-end interface with a clean layout for managing notes and a back-end API for handling data storage.

## Features

- **View Notes**: Access your saved notes from the Notes page.
- **Add Notes**: Create new notes with a title and text.
- **Save Notes**: Save new notes with a unique identifier.
- **View Existing Notes**: See a list of all your existing notes.
- **Clear Form**: Clear the form fields when you want to start a new note.
- **Responsive Design**: Accessible and usable on various devices.

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm (Node Package Manager)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/note-taker.git
   cd note-taker

2. **Install Dependencies**

- npm install

3. **Start the Server**
- npm start

## File Structure
- public/: Contains static files such as HTML, CSS, and JavaScript.
- index.html: Landing page with a link to the Notes page.
- notes.html: Page for viewing and managing notes.
- assets/: Static assets like styles and scripts.
- db/: Contains the db.json file where notes are stored.
- server.js: Main server file using Express.js to handle routes and API requests.

## API Routes
- GET /notes: Serves the notes.html file.
- GET /api/notes: Retrieves all saved notes from db.json.
- POST /api/notes: Adds a new note to db.json and returns the new note.


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or feedback, please contact talitarosa.02@hotmail.com

