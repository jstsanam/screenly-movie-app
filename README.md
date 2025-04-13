# Screenly🎬
A mobile app for movie lovers to explore, search, and save their favorite films. Built using React Native and Expo, Screenly delivers a smooth and visually engaging experience with real-time movie data and a smart popularity algorithm powered by Appwrite.

## 📋 <a name="table">Table of Contents</a>
1. 📝 [About the Project](#about)
2. 🔥 [Features](#features)
3. 🛠️ [Tech Stack](#tech-stack)
4. 📁 [Project Structure](#project-structure)
5. ⚙️ [Installation](#installation)
6. 🌍 [Environment Variables](#envs)
7. 📲 [Tabs](#tabs)
8. 📩 [Contact](#contact)

## <a name="about">About the Project 📝</a>
Screenly is a React Native mobile application that allows users to discover movies, search through an extensive library, and save their favorites for later viewing. It integrates real-time data fetching and a smart popularity ranking system based on user searches. With a sleek UI powered by Tailwind CSS and NativeWind, Screenly provides an immersive and scalable experience across devices.

## <a name="features">Features 🔥</a>
- **Real-time data:** Fetching and displaying real-time movie data
- **Home Page:** Featured and discover movies
- **Search Page:** Search for your favorite movies
- **Popularity algorithm:** Track user searches to display the most searched movies

## <a name="tech-stack">Tech Stack 🛠️</a>
- **Mobile Framework:** React Native (Expo)
- **Language:** TypeScript
- **Backend & Database:** Appwrite
- **API Integration:** TMDB API
- **Styling:** Tailwind CSS with NativeWind

## <a name="project-structure">Project Structure 📁</a>
```bash
/app                → Main application directory  
/assets             → Static assets like images and icons  
/components         → Reusable UI components  
/constants          → App-wide constants  
/interfaces         → TypeScript interfaces for type safety  
/services           → API and Appwrite service functions  
/types              → Shared type definitions  
```

## <a name="installation">Installation ⚙️</a>
1. Clone the repository:
```bash
git clone https://github.com/jstsanam/screenly-movie-app.git
```
2. Navigate to the project directory:
```bash
cd screenly-movie-app
```
3. Install dependencies:
```bash
npm install
```
4. Run the application:
```bash
npx expo start
```
Scan the QR code using the Expo Go app on your mobile device.

## <a name="envs">Environment Variables 🌍</a>
| Variable Name                       | Description                               | Example Value         |
|-------------------------------------|-------------------------------------------|-----------------------|
| EXPO_PUBLIC_MOVIE_API_KEY           | TMDB API key                              | your_tmdb_api_key     |
| EXPO_PUBLIC_APPWRITE_PROJECT_ID     | Appwrite project ID                       | your_project_id       |
| EXPO_PUBLIC_APPWRITE_DATABASE_ID    | Appwrite database ID                      | your_database_id      |
| EXPO_PUBLIC_APPWRITE_COLLECTION_ID  | Appwrite collection ID                    | your_collection_id    |

## <a name="tabs">Tabs 📲</a>
### 1. Home
- Discover all available movies.
- Trending movies highlighted at the top.
- Tap to view full movie details.
### 2. Search
- Search for any movie with instant results.
- Display list of searched movies dynamically.
### 3. Saved
- View your saved/bookmarked movies in one place.
### 4. Profile
- Manage your profile details.

## <a name="contact">Contact 📩</a>
Sanam Yadav - [jstsanam@gmail.com](mailto:jstsanam@gmail.com)  
GitHub: [jstsanam](https://github.com/jstsanam)
