# usePopcorn

usePopcorn is a React application that allows users to search for movies, view their details, and manage a list of watched movies. The app uses the OMDB API to fetch movie data.

## Features

- **Movie Search**: Search for movies by entering a keyword in the search bar.
- **Search Results**: View search results with movie posters, titles, and release years.
- **Movie Details**: Click on a movie to view detailed information, including synopsis, cast, director, genre, and IMDb rating.
- **Movie Rating**: Add your own rating for a movie using a star-based rating system.
- **Watched Movies List**: Add movies to your watched list and view statistics like average runtime, average IMDb rating, and your average rating.

## Technologies Used

- **React**: JavaScript framework for building user interfaces.
- **Vite**: Fast development tool for modern web applications.
- **OMDB API**: API used to fetch movie data.
- **CSS**: Custom styles for a responsive and visually appealing UI.

## Installation

1. Clone this repository:

   ```bash
   git clone <REPOSITORY_URL>
   cd usepopcorn
   ```bash
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser at:
   ```
   http://localhost:5173
   ```

## Available Scripts

- `npm run dev`: Starts the app in development mode.
- `npm run build`: Builds the app for production.
- `npm run preview`: Previews the production build.
- `npm run lint`: Runs ESLint to check for code issues.

## Project Structure

```
usepopcorn/
├── src/
│   ├── App.jsx          # Main application component
│   ├── Appv2.jsx        # Enhanced version of the application
│   ├── StarRating.jsx   # Star rating component
│   ├── main.jsx         # Application entry point
│   ├── index.css        # Main styles
├── public/              # Static files
├── .gitignore           # Git ignore rules
├── eslint.config.js     # ESLint configuration
├── vite.config.js       # Vite configuration
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
```

## OMDB API Configuration

To use the application, you need to configure an OMDB API key. Replace the `KEY` value in `src/Appv2.jsx` with your own API key:

```jsx
const KEY = 'YOUR_API_KEY';
```

## Contribution

Contributions are welcome! If you'd like to contribute, please open an issue or submit a pull request.
