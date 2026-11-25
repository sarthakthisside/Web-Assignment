# Personal Portfolio Website

A responsive personal portfolio built with **HTML5 and CSS3**, with a small amount of vanilla JavaScript for the mobile navigation menu and demo contact-form interaction.

The website introduces Sarthak, highlights areas of interest and skills, showcases sample projects, and provides a contact section.

## Overview

- **Stack:** HTML5, CSS3, vanilla JavaScript
- **Styling:** Custom CSS, Flexbox, media queries, Google Fonts (Poppins)
- **Dependencies:** No frameworks or package installation required
- **Entry point:** `index.html`

## Features

- Sticky navigation with section links
- Hero and About sections
- Skills cards with visual progress bars
- Project cards for portfolio and sample programming projects
- Contact form with browser-side required-field and email validation
- Mobile navigation menu
- Responsive layouts for desktop, tablet, and mobile screens
- Smooth scrolling and hover transitions

## Project Structure

```text
Web-Assignment/
├── index.html    # Page structure and content
├── style.css     # Layout, styling, and responsive rules
└── README.md     # Project documentation
```

The HTML references optional images under an `assets/` directory (for example, `assets/profile.png`, `assets/about.jpg`, and the project screenshots). That directory is not currently included in the repository. Add your own image files at those paths if you want to use them; otherwise, the page's image fallbacks will be shown.

## Run Locally

No build tools or dependencies are needed.

1. Clone the repository:

   ```bash
   git clone https://github.com/sarthakthisside/Web-Assignment.git
   ```

2. Open the project folder:

   ```bash
   cd Web-Assignment
   ```

3. Open `index.html` in your browser.

   Alternatively, use the **Live Server** extension in Visual Studio Code for a local development server.

## Customisation

Update the content directly in `index.html`:

- Edit the introduction and About section.
- Replace the example skills and progress values with your current skills.
- Update project names, descriptions, and links.
- Replace the placeholder contact details and social profile URLs.
- Add your images to an `assets/` folder and keep the filenames in the HTML in sync.

Adjust colours, spacing, typography, cards, and responsive breakpoints in `style.css`.

> **Contact form note:** The current form is a front-end demo. It validates required fields in the browser, displays a confirmation alert, and resets the form; it does not send messages to an email address or backend service.

## Deploy with GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/(root)` folder, then save.
5. Once GitHub Pages finishes deploying, use the published URL shown in the Pages settings.

## Learning Goals

This assignment demonstrates foundational front-end concepts, including semantic page structure, reusable CSS classes, Flexbox layouts, responsive design, navigation links, form validation, and basic DOM interaction.

---

Made with HTML, CSS, and a little JavaScript.
