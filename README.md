# 🎬 PopFlix

**PopFlix** is a modern movie discovery app built with **React** and powered by **Appwrite** on the backend. It uses **The Movie Database (TMDb)** API to provide real-time movie search and trending movie data with an optimized debounce search experience.


---

![PopFlix](./localhost_5174_.png)

---

## 🚀 Features

- 🔎 Optimized **debounced search**
- 🔥 Shows **trending movies**
- 🎬 Explore **popular movies**
- ⚡ Fast and responsive UI
- 📈 Search tracking via **Appwrite**

---

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Appwrite
- **API**: TMDb (The Movie Database)
- **Utils**: `react-use`, `fetch`, debounce hooks

---

## 📦 Installation & Setup


To get PopFlix up and running on your local machine:

1. **Make sure you have Node.js and npm installed.**  
   You can download them from [https://nodejs.org](https://nodejs.org).

2. **Clone this repository** to your computer:

   ```bash
   git clone https://github.com/ilaibasheikh/popflix.git

3. **Navigate to the project directory** by opening your terminal or command prompt and typing:

   > `cd popflix`

4. **Setup Appwrite Backend** 
   
    Go to Appwrite Cloud Console

    Create a new project.
Enable the Database service.
Create a collection for movies or searches with fields like:
    > `title (String)
        poster_url (String)
        search_count (Integer)`

    Configure read/write permissions to allow your frontend app to interact.

5. **Update .env file** 
   
    VITE_TMDB_API_KEY=your_tmdb_read_access_token
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id

6. **Install the dependencies** required for the project.  
   In the terminal, run:

   > `npm install`  
   This will download all packages listed in `package.json` and set up your `node_modules` folder.

7. **Start the application** by running:

   > `npm run dev`  
   This will launch the development server and open the app in your default browser.

---