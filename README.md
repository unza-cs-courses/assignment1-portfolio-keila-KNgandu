# CSC4035 Assignment 1: Responsive Portfolio Website

**Name:** Keila Ngandu  
**Student ID:** 2022009908 
**Design Theme:** Modern professional with soft pink accent – clean, secure/tech-inspired layout using dark slate and vibrant accent colors for a trustworthy yet creative feel.

## CSS Techniques Used
- CSS Custom Properties (CSS Variables) for colors, spacing, and radii
- Flexbox (header navigation, about section, contact layout, footer)
- CSS Grid (projects gallery and skills list)
- Mobile-first responsive design with 3+ breakpoints
- CSS-only hamburger menu (mobile navigation)
- Dark/Light mode toggle (with `prefers-color-scheme` support + manual button)
- Smooth CSS transitions and hover animations
- Print stylesheet for clean printing

## Challenges & Solutions
- **Challenge:** Making navigation mobile-friendly without JavaScript.  
  **Solution:** Used the CSS checkbox hack with a hamburger icon that transforms into a close icon. The menu slides down smoothly on mobile.

- **Challenge:** Implementing a reliable dark/light mode without external libraries.  
  **Solution:** Combined `prefers-color-scheme` media query (respects system preference) with a toggle button that adds a `dark` class to `<html>`. Used CSS variables for easy theme switching.

- **Challenge:** Ensuring good contrast and accessibility across themes.  
  **Solution:** Defined separate color palettes in `:root` and `.dark`, tested with browser dev tools.

- **Challenge:** Keeping the design professional while showing personality.  
  **Solution:** Used a soft pink accent (`#f4a6c5`) against dark slate backgrounds for a modern cybersecurity/tech feel.

## Credits
- Profile and project placeholder images: 
- All code written from scratch – no CSS frameworks used.
- Inspiration from modern portfolio designs (clean typography + subtle animations).

## Screenshots
- `screenshots/mobile.png`
- `screenshots/tablet.png`
- `screenshots/desktop.png`


## Extension 

- Dark/light mode toggle with CSS 
- CSS animations/transitions 
- CSS-only hamburger menu 
- Print stylesheet 