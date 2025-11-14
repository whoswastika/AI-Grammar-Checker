📖 About

AI Grammar Checker is a powerful writing assistant that analyzes text, detects grammar issues, spelling mistakes, and improves sentence quality using the OpenAI API.
It offers real-time suggestions and corrections through a clean and responsive UI built with React and Tailwind CSS, supported by a fast Node.js + Express backend.

This tool is perfect for students, writers, developers, and anyone who wants clean and professional text.

🚀 Features

🔍 Grammar Correction – Instantly fix grammar issues in your text.
📝 Spell Checker – Detects and corrects spelling mistakes accurately.
🔄 Sentence Rephrasing – Suggests improved versions of sentences.
⚡ Real-time Analysis – Fast responses powered by OpenAI.
🎨 Clean & Minimal UI – Simple and modern interface.
🔔 Toast Notifications – Real-time feedback on actions.
🧩 Modular Backend – Separate routes for grammar, spelling, and full text analysis.

🛠 Tech Stack
Frontend

⚛️ React.js – UI Framework
🎨 Tailwind CSS – Styling
🔄 Axios – API Requests
⚡ Vite – Fast development server

Backend

🟩 Node.js – Server environment
🚏 Express.js – API routes
🧠 OpenAI API – Grammar & text improvement model

🔧 Setup Instructions
Clone the repository
git clone https://github.com/your-username/AI-Grammar-Checker.git
cd AI-Grammar-Checker/GrammerAssistant

🧩 Backend Setup
cd server
npm install

Add your OpenAI API key

Create a .env file in /server:

OPENAI_API_KEY=your_key_here
PORT=5000

Start the backend
npm start

🎨 Frontend Setup
cd ../client
npm install
npm run dev

🌐 API Integration
Endpoints Used

✉️ Grammar Checker

POST /grammar


🔤 Spell Checker

POST /spell


🧠 Full Text Analysis

POST /analyze

🧪 Testing

To run backend or frontend tests (if implemented):

npm test

📧 Contact

For any inquiries or improvements, feel free to reach out:

📩 Email: swastikad164@gmail.com

💻 GitHub: https://github.com/whoswastika
