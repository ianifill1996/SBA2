## Project Overview
This project is a fully responsive and accessible website designed with inclusivity and usability in mind. It implements semantic HTML, accessible forms, proper heading structure, and color contrast standards to ensure that users of all abilities—including those who use screen readers or keyboard navigation—can navigate and interact with the site effectively.

## Key Accessibility Features

### Semantic HTML
- Uses `<header>`, `<main>`, `<nav>`, `<section>`, `<article>`, and `<footer>` for meaningful structure.
- Provides better screen reader support and SEO by giving context to each part of the page.

### Responsive Design
- Utilizes **Flexbox** and **media queries** to adapt layouts for mobile, tablet, and desktop screens.
- Ensures a consistent user experience across devices.

### Visual Accessibility
- All text and background color combinations meet or exceed WCAG 2.1 **AA contrast ratio** standards (4.5:1 for normal text).
- No information is conveyed by color alone—icons or text labels are used to support visual cues.

### Screen Reader & Keyboard Support
- All interactive elements (links, buttons, inputs) are reachable via keyboard.
- Includes appropriate ARIA roles and attributes (where necessary).
- Headings (`<h1>`, `<h2>`, etc.) follow a clear and logical order to help screen reader navigation.

### Forms
- Inputs are paired with `<label>` elements using `for` and `id` attributes.
- Related fields are grouped with `<fieldset>` and `<legend>` for context.
- Placeholders are used to guide input but not relied on for labeling.