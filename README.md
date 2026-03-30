# Rent vs. Buy Simulator

A fully accessible, multi-theme financial simulation engine built for Hackonomics 2026. This application helps users determine the true opportunity cost of renting versus buying a home by calculating compound interest, loan amortization, and sunk costs over a customizable timeline.

## Features

*   **Core Financial Engine**: Runs a month-by-month simulation comparing home equity growth against a liquid stock market portfolio.
*   **Educational Module**: Simplifies complex economic concepts (Opportunity Cost, Liquidity, Inflation Hedge) into digestible index cards.
*   **Advanced Theme System**: CSS-variable based theming including Editorial Minimal (default), Dreamy Y2K, Night Study, and a strict Colorblind-safe high-contrast mode.
*   **Micro-interactions**: Integrates GSAP for smooth data visualization and number counting.
*   **WCAG Accessibility**: 
    *   Fully keyboard navigable with visible focus rings.
    *   Semantic HTML architecture.
    *   Debounced `aria-live` regions for clean screen reader announcements.
    *   Visual animations (`aria-hidden`) decoupled from screen reader text (`sr-only`) to prevent audio spam.

## Tech Stack

*   HTML5 (Semantic & Accessible)
*   CSS3 (Custom Properties / Variables)
*   Vanilla JavaScript (ES6+)
*   GSAP (GreenSock Animation Platform)

## Running Locally

This project requires no build steps or package managers.

1. Open `index.html` in any modern web browser.

## Future Roadmap

*   Backend integration utilizing **Momen.app** for user authentication.
*   Ability to save custom financial parameters to a user dashboard.
*   Exportable PDF reports for financial planning.

## License

This project was built for the Hackonomics 2026 Hackathon.
