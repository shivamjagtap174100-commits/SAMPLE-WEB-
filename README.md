# FoodStays

FoodStays is a responsive, single-page website concept for discovering restaurants and dining experiences inside nearby hotels. The page brings hotel information, food highlights, ratings, and sample prices together in one place so visitors can browse different kinds of dining.

## What this project includes

- A branded navigation bar and introductory section for the FoodStays concept.
- A search area with a dish, hotel, or cuisine text field and distance choices.
- Six sample hotel and dining cards with locations, food categories, signature dishes, ratings, estimated distances, and sample prices.
- Category tabs for all stays, buffets, rooftop lounges, fine dining, and breakfast or cafes. The tabs filter cards using CSS radio buttons and selectors, without JavaScript.
- A sample tasting-menu popup that opens and closes with a CSS checkbox toggle.
- A responsive layout that adapts the navigation and search area on smaller screens.
- A footer with example cuisine categories and cities.

## Built with

- HTML for the page content and structure.
- CSS for layout, styling, responsive behavior, category filtering, and the popup.
- Google Fonts and remote Unsplash images for visual presentation.

No framework, package manager, or build step is required.

## Project files

- `web.html` contains the complete page markup and the main embedded stylesheet.
- `web.css` contains an additional buffet-filter CSS rule. The HTML currently embeds its styles directly, so this standalone stylesheet is not linked from the page.
- `README.md` describes the project and how to view it.

## Run locally

Open `web.html` in a browser. An internet connection is needed to load the external Google Fonts and Unsplash images.

## Prototype notes

This repository is a front-end demonstration, not a connected hotel-discovery service. The displayed properties, reviews, distances, prices, menu, and contact number are sample content; they are not verified live listings. The search field, distance selector, and reservation link are visual examples and are not connected to search, location, booking, or a backend. Category filtering and opening or closing the sample menu popup work entirely in CSS.
