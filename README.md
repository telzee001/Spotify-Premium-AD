# Spotify Premium Ad UI Recreation

A responsive promotional advertisement interface inspired by music-streaming advertisements and recreated independently using HTML and CSS.

This project was built as a frontend practice exercise to improve my ability to visually analyze an existing interface, break it into components, and recreate the design using the HTML and CSS concepts I have learned.

## Project Overview

The goal of this project was not to create a functional Spotify application, but to practice translating a visual reference into a responsive web interface.

The page contains:

- A promotional advertisement card
- Spotify-inspired branding
- Promotional headline and typography
- Responsive promotional imagery
- Call-to-action button
- Full-page background presentation
- Responsive behavior across desktop and mobile screen sizes
- Mouse hover and keyboard focus states

## Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Media Queries
- Google Fonts
- Font Awesome
- Chrome DevTools

## What I Practiced

This project helped me practice:

- Breaking a visual design into smaller UI components
- Building layouts with Flexbox
- Creating responsive component sizing
- Using `width` and `max-width` together for fluid layouts
- Creating responsive images with `max-width` and automatic aspect-ratio preservation
- Adjusting typography for smaller viewports with media queries
- Working with custom fonts
- Using icon libraries
- Styling interactive button states
- Supporting keyboard navigation with `:focus-visible`
- Testing layouts at different viewport widths using browser DevTools
- Debugging horizontal overflow and fixed-width layout problems

## Responsive Design

One of the main challenges in this project was making the advertisement maintain its desktop appearance while still adapting to very narrow screens.

The card uses fluid sizing with a maximum desktop width, allowing it to shrink when the available viewport becomes smaller.

The promotional image also scales with its container while preserving its aspect ratio.

The interface was manually tested at desktop, tablet, mobile, and narrow mobile viewport sizes, including approximately 290px wide.

## Accessibility

The call-to-action button includes visible keyboard focus feedback using the `:focus-visible` pseudo-class.

This allows keyboard users navigating with the Tab key to clearly identify when the button has focus.

The project also uses alternative text for its promotional image.

## Project Structure

    spotify-ad/
    ├── index.html
    ├── style.css
    └── README.md

## Key Lesson

The biggest lesson from this project was that responsive design is not simply about making elements smaller.

A responsive component needs appropriate sizing constraints so that it can preserve its intended appearance when space is available while adapting gracefully when the viewport becomes smaller.

During development, fixed minimum sizing caused the advertisement card to overflow on mobile devices. The layout was reworked using fluid width constraints and responsive image sizing, allowing the same component to work from desktop screens down to very narrow mobile viewports.

## Status

Completed.

This project is part of my ongoing frontend and software development learning portfolio.

## Disclaimer

This is an independent educational UI recreation created for frontend development practice.

Spotify branding and related trademarks belong to their respective owners. This project is not affiliated with, endorsed by, or an official product of Spotify.