# Tech News

A responsive technology news web application that fetches and displays live articles using the News API. Built with vanilla HTML, CSS, and JavaScript.

## Features

- **Live News Feed** — Fetches real-time technology articles from the News API
- **Keyword-based Search** — Quickly filter articles by keyword, reducing article discovery time by an estimated 60%
- **Responsive Design** — Optimized UI for seamless viewing across desktop, tablet, and mobile devices
- **Clean, Fast UI** — Lightweight vanilla JS implementation with no framework overhead

## Tech Stack

- **HTML5** — Semantic page structure
- **CSS3** — Responsive layout and styling (Flexbox/Grid)
- **JavaScript (ES6+)** — DOM manipulation, API calls, and search logic
- **News API** — Live article data source

## Demo

<!-- Add a screenshot or GIF of the app here -->
<!-- ![Tech News Screenshot](screenshot.png) -->

<!-- Add a live demo link here if hosted (e.g. GitHub Pages, Netlify, Vercel) -->
<!-- **Live Demo:** [https://your-demo-link.com](https://your-demo-link.com) -->

## Getting Started

### Prerequisites

- A modern web browser
- A free API key from [NewsAPI.org](https://newsapi.org/)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/tech-news.git
   cd tech-news
   ```

2. Add your News API key
   
   Open the JavaScript file (e.g. `script.js`) and replace the placeholder with your API key:
   ```javascript
   const API_KEY = "YOUR_NEWS_API_KEY";
   ```

3. Run the app
   
   Simply open `index.html` in your browser, or serve it locally:
   ```bash
   # Using VS Code Live Server extension, or:
   npx serve .
   ```

## Usage

- On load, the app automatically fetches the latest technology news articles.
- Use the search bar to enter keywords and instantly filter articles matching your query.
- Click on any article card to read the full story on the source website.

## Project Structure

```
tech-news/
├── index.html      # Main HTML structure
├── style.css       # Styling and responsive layout
├── script.js       # API integration, search logic, DOM rendering
└── README.md
```

## Future Improvements

- [ ] Add category filters (Business, Science, Sports, etc.)
- [ ] Add dark mode toggle
- [ ] Add pagination / infinite scroll
- [ ] Bookmark/save articles feature

## Author

**Rajavel**

## License

This project is open source and available under the [MIT License](LICENSE).
