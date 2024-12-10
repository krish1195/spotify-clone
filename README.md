# Spotify Clone

A modern music streaming web application built with React, Redux, and the Shazam Core API. This project features a responsive design, real-time music playback, and various music discovery features.

## 🚀 Features

- **Music Playback**: Full-featured audio player with play, pause, next, and previous controls
- **Discover Page**: Browse music by genres with dynamic filtering
- **Search Functionality**: Search for songs and artists
- **Top Charts**: View trending songs and top artists
- **Geo-Location**: Location-based music recommendations
- **Artist Pages**: Detailed artist information and related songs
- **Song Details**: View song lyrics and related tracks
- **Responsive Design**: Mobile-friendly interface with smooth animations

## 🛠️ Technologies Used

- **Frontend Framework**: React.js
- **State Management**: Redux Toolkit
- **API Integration**: RTK Query
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **APIs Used**:
  - Shazam Core API (RapidAPI)
  - Geo Location API

## ⚙️ Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/spotify-clone.git
cd spotify-clone
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with your API keys:
```env
VITE_SHAZAM_CORE_RAPID_API_KEY=your_rapidapi_key
VITE_GEO_API_KEY=your_geo_api_key
```

4. Start the development server:
```bash
npm run dev
```


## 🔧 Configuration Files

- **vite.config.js**: Vite build configuration
- **tailwind.config.js**: Tailwind CSS customization
- **postcss.config.js**: PostCSS plugins configuration

## 🎯 Core Features Implementation

### Music Player
- Implements full music playback functionality
- Manages player state through Redux
- Supports playlist continuation

### API Integration
- Uses RTK Query for efficient API calls
- Implements caching and request deduplication
- Handles various data formats and responses

### Responsive Design
- Custom Tailwind configurations
- Smooth animations and transitions
- Mobile-first approach

## 🚦 State Management

- **Player State**: Manages current song, playlist, and playback status
- **API State**: Handles API calls and responses
- **UI State**: Manages loading states and user interactions

## 🎨 Styling

Custom Tailwind configurations include:
- Custom color schemes
- Animation utilities
- Responsive breakpoints
- Dark theme support

## 📝 Development Notes

- Environment variables must be prefixed with `VITE_`
- Uses Redux Toolkit's createApi for API integration
- Implements error boundaries for robust error handling
- Features responsive design patterns

## 🔄 API Integration

### Shazam Core API Endpoints:
- World Charts
- Genre-based Charts
- Country-specific Charts
- Artist Details
- Song Details
- Search Functionality
- Related Tracks

## 🏗️ Future Improvements

1. User Authentication
2. Playlist Creation
3. Offline Mode
4. Social Sharing Features
5. Enhanced Music Recommendations
6. User Profile Management

## ⚠️ Common Issues

1. API Rate Limits
   - Solution: Implement request throttling

2. Music Playback
   - Ensure proper audio format support
   - Handle network interruptions

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Shazam Core API
- RapidAPI Platform
- React Community
- Redux Team
