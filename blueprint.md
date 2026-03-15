
# ozc sound - Blueprint

## Overview

A simple, visually appealing single-page application that displays the text "ozc sound" and includes a dark mode toggle feature.

## Style, Design, and Features

*   **Typography:** Modern, clean, and readable font (Poppins from Google Fonts).
*   **Color Palette:**
    *   **Light Mode:**
        *   Background: `#f0f0f0`
        *   Text: `#333`
        *   Primary/Accent: `#007bff`
    *   **Dark Mode:**
        *   Background: `#1a1a1a`
        *   Text: `#f0f0f0`
        *   Primary/Accent: `#007bff`
*   **Layout:** Centered content with ample spacing for a clean, minimalist look.
*   **Components:**
    *   **Title:** "ozc sound" displayed prominently.
    *   **Dark Mode Toggle:** A stylish button with an icon that switches between light and dark themes.
*   **Effects:**
    *   Subtle background noise texture for a premium feel.
    *   Soft, deep shadows on the main content and a "glow" effect on the interactive toggle button.

## Current Plan

1.  **`index.html`:**
    *   Set the page title to "ozc sound".
    *   Import the "Poppins" font from Google Fonts.
    *   Add a main container for the content.
    *   Include a `<h1>` for "ozc sound" and a button for the dark mode toggle.
    *   Link to `style.css` and `main.js`.
2.  **`style.css`:**
    *   Define CSS variables for colors in both light and dark modes.
    *   Apply a background texture.
    *   Style the main container, title, and toggle button with modern CSS, including shadows and transitions.
3.  **`main.js`:**
    *   Add an event listener to the toggle button.
    *   Implement the logic to switch the theme by toggling a class on the `body` element.
    *   Use `localStorage` to persist the selected theme across sessions.
