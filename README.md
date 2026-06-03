# Plant-album

A responsive, single-page botanical encyclopedia built with semantic HTML and pure CSS. This project catalogs vegetables, herbs, shrubs, trees, and spices, providing scientific names and health benefits for each entry.

Key Features :

- Zero JavaScript Navigation: Uses the CSS `:target` pseudo-class to show/hide plant details, creating a dynamic single-page app experience without scripting.
- Semantic Structure: Organized by plant categories with anchor-based linking for seamless in-page navigation.
- Responsive Design: Fluid image sizing and flexible layouts ensure usability across mobile and desktop screens.
- Interactive States: Distinct `:hover` and `:visited` styles provide clear visual feedback for user actions.

Technical Highlights :

- CSS State Management: Implements `section:target { display: block; }` to handle view transitions.
- Flexible Layouts: Uses `max-width`, `vw/vh` units, and centered containers for adaptive sizing.
- Consistent Theming: Earthy color palette (teal, slate, coral) applied via reusable class selectors.

Live Demo :

View Project: https://obasililian59-cell.github.io/Plant-album/

Project Structure

```
plant-album/
├── index.html
├── plant.css
├── images/
└── README.md
```


