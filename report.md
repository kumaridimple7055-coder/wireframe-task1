# Project Report: Transforming Wireframes into Static Web Pages

## 1. Approach & Design Decisions
- **Semantic HTML:** Utilized proper structural elements like `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` to improve web accessibility (a11y) and SEO friendliness.
- **Layout Strategy:** Employed **CSS Flexbox** for alignment in the header navigation and **CSS Grid** for structuring the feature cards section flexibly across devices.
- **Color Scheme:** Picked a professional palette featuring deep slate (`#2c3e50`) for structure, vibrant blue (`#3498db`) for branding highlights, and a contrasting accent color (`#e74c3c`) for call-to-action buttons.

## 2. Challenges Encountered
- **Responsive Alignment:** Maintaining proper spacing and proportions for content cards on intermediate tablet screens.
- **Header Overflow:** Ensuring navigation links do not wrap awkwardly on smaller mobile viewports.

## 3. Resolutions
- Utilized CSS Grid with `auto-fit` and `minmax()` properties, allowing cards to stack seamlessly without hardcoding fixed breakpoints.
- Implemented media queries to shift the header layout to a vertical stack on screens smaller than 768px, ensuring optimal user experience.
-