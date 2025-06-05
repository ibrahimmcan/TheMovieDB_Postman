# 🎬 The Movie Database (TMDB) API Test Cases

A comprehensive test suite for The Movie Database API endpoints, covering user authentication, movie management, and search functionality.

## 📋 Test Cases Overview

### Authentication & Account Management
- **Get Account Details** - Retrieve user account information
- **Add Movie to Favorites** - Add movies to user's favorite list
- **Add Movie to Watchlist** - Add movies to user's watchlist
- **Get Favorite Movies** - Retrieve user's favorite movies
- **Get Rated Movies** - Retrieve user's rated movies
- **Get Watchlist Movies** - Retrieve user's watchlist

### Movie Discovery & Information
- **Get Movie Genres** - Retrieve official movie genre list
- **Get Now Playing Movies** - Movies currently in theaters
- **Get Popular Movies** - Popular movies list
- **Get Top Rated Movies** - Top rated movies list
- **Get Upcoming Movies** - Upcoming movies list
- **Get Movie Details** - Detailed movie information

### Search & Rating
- **Search Movies** - Search for movies by query
- **Search Keywords** - Search for movie keywords
- **Add Movie Rating** - Rate a movie
- **Delete Movie Rating** - Remove movie rating

### Security Testing
- **Unauthorized Access** - Test authentication failure scenarios

## 🔧 API Endpoints Tested

| Endpoint | Method | Purpose |
|----------|---------|---------|
| `/account` | GET | Get account details |
| `/account/{id}/favorite` | POST | Add to favorites |
| `/account/{id}/watchlist` | POST | Add to watchlist |
| `/movie/now_playing` | GET | Current movies |
| `/movie/popular` | GET | Popular movies |
| `/search/movie` | GET | Search movies |
| `/movie/{id}/rating` | POST/DELETE | Rate/unrate movie |

## 👥 Contributors

| 👤 Contributor                                          | 🛠️ Role            |
|---------------------------------------------------------|---------------------|
| [İbrahim Can](https://github.com/ibrahimmcan)           | Team Lead QA Tester |
| [Hakan Mert](https://github.com/hakan-mert)             | QA Tester           |
| [Ennur Göl](https://github.com/ennur7)                  | QA Tester           |
| [Serkan Sewoester](https://github.com/SerkanSewoester)  | QA Tester           |
| [Murat Öksüz](https://github.com/muratoksuz)            | QA Tester           |
| [Tuğba Yılmaz](https://github.com/MTY-EEE)              | QA Tester           |
| [Ayşenur Can](https://github.com/aysenur-g-c)           | QA Tester           |
| [Burak Bora Durmaz](https://github.com/burakboradurmaz) | QA Tester           |

## 🚀 Getting Started

1. Obtain a valid API key from [The Movie Database](https://www.themoviedb.org/settings/api)
2. Set up authentication tokens for account-specific endpoints
3. Run test cases against the TMDB API endpoints
4. Verify expected responses and error handling

## 📝 Test Results

Each test case includes:
- **Input Parameters** - Required authentication tokens, IDs, and query parameters
- **Expected Output** - Anticipated response format and status codes
- **Error Scenarios** - Authentication failures and invalid requests

---

*This test suite ensures comprehensive coverage of The Movie Database API functionality and proper error handling.*
