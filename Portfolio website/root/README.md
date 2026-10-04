# Alex Morgan Portfolio

A responsive static portfolio website built with HTML5, Bootstrap 5 and SCSS.

## Pages
- `index.html` — Home
- `about.html` — About + tech stack
- `contact.html` — Contact information

## Project structure
```text
portfolio-website/
├── index.html
├── about.html
├── contact.html
├── css/
│   └── style.css
├── scss/
│   └── style.scss
└── README.md
```

## Compile SCSS
Install Sass:
```bash
npm install -g sass
```

Then run:
```bash
sass scss/style.scss css/style.css --watch
```

For a one-time production build:
```bash
sass scss/style.scss css/style.css --style=compressed
```

Bootstrap is loaded from the official jsDelivr CDN, so an internet connection is required for Bootstrap CSS/JS unless you later download and host those files locally.

## Replace placeholders
Search for:
- `Alex Morgan`
- `hello@example.com`
- `+91 90000 00000`
- `India`

and replace them with your real details.
