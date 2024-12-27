PDF Merger Webpage

This project is a web-based application that allows users to merge multiple PDF files into a single PDF. The application is built using HTML, Bootstrap for styling, and Node.js for backend functionality.

Features

Upload multiple PDF files.

Drag-and-drop functionality for file uploads.

Rearrange uploaded PDFs before merging.

Merge PDFs into a single file.

Download the merged PDF.

Responsive design powered by Bootstrap.

Tech Stack

Frontend: HTML, CSS, JavaScript, Bootstrap

Backend: Node.js, Express.js

Libraries:

multer for handling file uploads.

pdf-lib for merging PDFs.

Installation

Prerequisites

Ensure you have the following installed:

Node.js

npm

Steps

Clone the repository:

git clone https://github.com/your-username/pdf-merger-webpage.git
cd pdf-merger-webpage

Install dependencies:

npm install

Start the server:

npm start

Open your browser and navigate to:

http://localhost:3000

Project Structure

pdf-merger-webpage/
├── public/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│       └── scripts.js
│   └── uploads/          # Temporary storage for uploaded files
├── views/
│   └── index.html        # Main HTML file
├── app.js                # Main Node.js server file
├── package.json          # Project metadata and dependencies
└── README.md             # Project documentation

Usage

Navigate to the web page.

Drag and drop PDF files or use the file picker to upload.

Rearrange the uploaded PDFs (if needed).

Click the Merge PDFs button.

Download the merged PDF file.

