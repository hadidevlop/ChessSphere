# ChessSphere
ChessSphere - The Next-Gen Chess Platform
📖 Description
ChessSphere is a complete, browser-based chess web application built as a single HTML file. It offers a premium, professional gaming experience with a sophisticated dark navy and gold theme. The platform allows users to play chess against another human in a local two-player mode or challenge a powerful, adaptive AI opponent powered by the Google Gemini API.

This project is more than just a game; it's a full-featured website designed for user engagement and learning. It includes multiple pages for content, a functional contact form for user feedback, and advanced in-game features like AI-powered hints and automatic post-game analysis, making it a comprehensive and ready-to-publish web application.

✨ Features
Complete Multi-Page Website: A full site structure with a homepage and separate pages for "About Chess," "How to Play," "Request Feature," and "Privacy Policy."

Two Game Modes:

Player vs. Player: Classic local multiplayer.

Player vs. AI: Challenge a sophisticated AI opponent.

Gemini-Powered AI:

Adjustable Difficulty: Choose between Easy, Medium, and Hard levels before starting a game against the AI.

AI-Powered Hints: Get a strategic move suggestion from the Gemini API at any point during the game.

Automatic Post-Game Analysis: The moment a game ends, Gemini automatically provides a detailed analysis, breaking down the opening, key moments, blunders, and brilliant moves.

Professional Gameplay Experience:

Drag-and-Drop: Intuitive drag-and-drop mechanics for moving pieces.

Legal Move Highlighting: Hovering over a piece instantly shows all of its possible legal moves.

Game State Logic: Automatically detects and announces checkmate and draws.

High-End Visuals & UI:

Premium Theme: A sophisticated dark navy blue and gold theme for a professional look.

High-Quality Pieces: A custom set of classic, professional-looking SVG chess pieces.

Classic Wooden Board: A visually appealing board with a traditional light and dark wood theme.

Functional Modals: Clean, modern pop-ups for instructions, AI difficulty selection, and game analysis.

Functional Contact Form: A "Request Feature" page with a working form that sends submissions directly to your email via Formspree.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6)

Styling: Tailwind CSS

Core Logic: jQuery, Chess.js, Chessboard.js

AI & Analysis: Google Gemini API

🚀 Setup & Configuration
This application is designed to be incredibly simple to set up as it is a single-file project.

Download: Simply save the index.html file to your local machine.

Run: Open the index.html file in any modern web browser.

Activating the Contact Form (Required)
To receive submissions from the "Request Feature" page, you must configure the Formspree endpoint.

Create a free account at formspree.io.

Create a new form and get your unique endpoint URL.

Open the index.html file, find the <form> tag with the id="request-form".

Replace the placeholder action="https://formspree.io/f/YOUR_FORM_ID" with your actual Formspree URL.

🌐 Deployment
This project can be deployed for free in minutes using services that host static sites.

Using GitHub Pages
Create a Repository: Create a new public repository on GitHub.

Upload: Upload the index.html file to the repository.

Enable Pages: In your repository's Settings, go to the Pages tab.

Select Branch: Under "Branch," select main and click Save.

Done! Your website will be live at your-username.github.io/your-repository-name within a few minutes.
