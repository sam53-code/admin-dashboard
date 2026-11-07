# admin-dashboard

A admin dashboard interface built with HTML5 and CSS3. The project features sidebar navigation, a header, project
overview cards, announcements, trending users and a footer.

## Features

- Sidebar navigation: Home, Profile, Message, History, Task and
  Community
- Header with search, notifications and administrator profile
- Project overview cards and status indicators
- Announcements and trending-user sections
- Footer with copyright, policy, support and version information
- Centralised CSS custom properties for consistent design
- CSS Grid and Flexbox layouts
- Responsive layout foundations
- SVG icons stored as external assets

## Technologies

- **HTML5** --- semantic page structure
- **CSS3** --- Grid, Flexbox, custom properties, transitions and media
  queries
- **SVG** --- scalable interface icons
- **Git** --- version control

## Project Structure

admin-dashboard/
├── index.html
├── css/
│ ├── root.css
│ └── dashboard.css
├── assets/
│ ├── icons/
│ │ ├── home.svg
│ │ ├── profile.svg
│ │ ├── message.svg
│ │ ├── history.svg
│ │ ├── task.svg
│ │ └── community.svg
│ └── images/
│ └── profile images and dashboard graphics
└── README.md

## Getting Started

1. Clone the repository

```bash
git clone <your-repository-url>
```

2. Open the project

Open the project directory in your preferred code editor.

3. Run the dashboard

Open `index.html` in a browser. For development, use a local server such
as the Live Server extension in Visual Studio Code.

## SVG Icons

SVG icons are stored in `assets/icons/`. For simple display, use an
image element:

External SVGs loaded through `<img>` do not expose their internal paths
to the page's CSS. For CSS-controlled single-colour icons, consider an
SVG mask:

Alternatively, use inline SVG with `fill="currentColor"` when direct
control of SVG paths is required.

## Development Roadmap

- [x] Establish initial HTML page structure
- [x] Define reusable CSS design tokens
- [x] Create the primary dashboard Grid layout
- [x] Add sidebar navigation markup and styling
- [x] Develop the header structure
- [x] Add project overview and information sections
- [x] Add the footer
- [ ] Complete responsive styling and test across screen sizes
- [ ] Implement interactive sidebar navigation
- [ ] Implement functional dashboard search
- [ ] Add notification and profile dropdown interactions
- [ ] Add dynamic project and user data
- [ ] Improve accessibility and keyboard navigation
- [ ] Perform cross-browser testing

## Learning Objectives

This project provides practical experience with semantic HTML, CSS Grid
and Flexbox, reusable design tokens, nested CSS, SVG assets and Git version control.

# Contributing

This is a personal learning project. When making changes:

1.  Create a branch for your work.
2.  Keep changes focused and use consistent naming.
3.  Test the dashboard at desktop, tablet and mobile widths.
4.  Use clear, descriptive commit messages.

# What I Practiced

- Structuring pages with semantic HTML
- Creating layouts with CSS Grid
- Aligning components with Flexbox
- Using CSS custom properties and design tokens
- Working with nested CSS rules
- Incorporating SVG assets
- Managing changes with Git

# Future Improvements

- [ ] Complete responsive layouts for desktop, tablet and mobile
- [ ] Implement interactive sidebar navigation
- [ ] Add functional dashboard search
- [ ] Add notification and profile dropdown interactions
- [ ] Populate project and user sections dynamically
- [ ] Improve keyboard navigation and accessibility
- [ ] Test across different browsers

# Acknowledgements

This project is part of The Odin Project open-source web development
curriculum, which provides a structured path for learning web
development through practical projects.

# License

Created for educational purposes as part of The Odin Project curriculum.
No separate license has been specified.
