📽️ Movie Project
A React-based movie web application that allows users to search, explore, and favorite movies using The Movie Database (TMDb) API.
<img width="1802" height="846" alt="Screenshot 2025-08-05 153333" src="https://github.com/user-attachments/assets/a2313549-5ab1-44f0-8d42-ecbced7b5aef" />
<img width="1805" height="837" alt="Screenshot 2025-08-05 153354" src="https://github.com/user-attachments/assets/9ad63d7a-7b1b-4a75-b457-b09d19c07301" />

🚀 Features
🔍 Search Movies by title

🎬 View Popular Movies

❤️ Favorite Button with click interaction

🎨 Clean and responsive UI using React

🌐 Fetch data using TMDb API

📁 Folder Structure
Movie-Project/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── MovieCard.js
│   ├── css/
│   │   └── MovieCard.css
│   ├── services/
│   │   └── api.js
│   ├── App.js
│   ├── Home.js
│   └── index.js
├── .gitignore
├── package.json
└── README.md

🛠️ Tech Stack
Frontend: React.js

Styling: CSS

API: TMDb API

🔐 Environment Variables:
Create a .env file in the root and add your TMDb API key:
```bash
REACT_APP_TMDB_API_KEY=your_tmdb_api_key_here
```
Then in your API file (api.js), access it via:
```bash
const API_KEY = process.env.REACT_APP_TMDB_API_KEY;

```

🔧 Setup Instructions
```bash
# Clone the repo
git clone https://github.com/murtuzamaaz/Movie-Proejct.git
cd Movie-Proejct

# Install dependencies
npm install

# Run the app
npm start
```

📌 TODO / Future Enhancements
✅ Show popular movies

✅ Add search functionality

🔲 Add genres and filters

🔲 Add user authentication for personalized favorites

🔲 Deploy to GitHub Pages or Netlify


