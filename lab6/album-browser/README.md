# Album Browser — Lab 6

An Angular SPA for browsing albums from the JSONPlaceholder REST API.

## Features
- Browse 100 albums from a live REST API
- View album details and edit titles
- Browse photos in a responsive grid
- Delete albums from the list
- Multi-page navigation with Angular Router

## How to Run

**Requirements:** Node.js 18+ and npm installed.

```bash
# 1. Install dependencies
npm install

# 2. Start the dev server
npm start

# 3. Open your browser at:
http://localhost:4200
```

## Project Structure

```
src/app/
├── models/
│   ├── album.model.ts
│   └── photo.model.ts
├── services/
│   └── album.service.ts
└── components/
    ├── home/
    ├── about/
    ├── albums/
    ├── album-detail/
    └── album-photos/
```

## Tech Stack
- Angular 17 (Standalone Components)
- Angular Router
- Angular HttpClient
- RxJS
- JSONPlaceholder API
