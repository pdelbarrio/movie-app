# Movie Search App

A React-based movie search application that allows users to discover and explore movies. The app features a modern UI, real-time search functionality, and displays trending movies.

## Features

- Real-time movie search with debouncing
- Trending movies section
- Responsive modern UI
- Movie details display with posters
- Integration with TMDB API
- Error handling and loading states

## Technologies Used

- React.js
- Vite
- TailwindCSS
- Appwrite
- React-use (for debouncing)

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- TMDB API key

### Installation

1. Clone the repository
```bash
git clone <your-repo-url>
cd movie-app2
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory and add your TMDB API key
```env
VITE_TMDB_API_KEY=your_api_key_here
```

4. Start the development server
```bash
npm run dev
```

## Usage

- Use the search bar to find movies
- View trending movies in the trending section
- Click on movie cards to view more details
- Enjoy a responsive and user-friendly interface

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## License

This project is open source and available under the [MIT License](LICENSE).
