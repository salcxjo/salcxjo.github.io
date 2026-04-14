# salcxjo.github.io

Personal website. Built with vanilla HTML and CSS — no frameworks, no build step, no tracking.

An ode to the early web and the era that got me interested in computers in the first place.

## Pages

| Page | Description |
|------|-------------|
| `/` | Homepage |
| `/projects/` | Computer projects — IoT, edge ML, embedded systems, web |
| `/books/` | Reading list — 78+ books across literary fiction, nature writing, Persian literature |
| `/poetry/` | A personal poetry collection, bilingual Persian/English |
| `/kayaking/` | Sea kayaking logs — Nova Scotia and Clayoquot Sound |
| `/skiing/` | Alpine, nordic, and ski touring |
| `/movement/` | Running and walking |

## Stack

Pure HTML and CSS throughout. A few pages use React via CDN for interactivity (skiing, movement) — no build step required, just open the file.

## Structure

```
salcxjo.github.io/
├── index.html
├── projects/
│   └── index.html
├── books/
│   └── index.html
├── poetry/
│   └── index.html
├── kayaking/
│   ├── index.html
│   └── img/
├── skiing/
│   └── index.html
└── movement/
    └── index.html
```

## Design

Each page has its own aesthetic — the homepage is a GeoCities throwback, the books page is warm sepia, the poetry page is a Persian rug, the projects page is a cut-and-paste zine, the skiing page is a mountain lodge. The constraint is intentional: vanilla HTML forces you to think carefully about what you actually need.

## Running locally

```bash
# any static server works — e.g.
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` directly in a browser.

---

*always under construction*
