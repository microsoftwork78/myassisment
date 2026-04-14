# myassisment
# Laundry Wallah

This repository contains a simple HTML page for a laundry service website called Laundry Wallah / Laundry Mart.

## Files

- `index.html` — the main page of the site.
- `laundry.png` — image shown on the page (expected to be in the same folder).

## What the code does

The HTML page includes:

- A page title set in the `<head>` section: `Laundry Wallah`.
- Inline CSS inside the `<style>` block to control the page appearance.
- A main heading (`<h1>`) that welcomes visitors.
- A descriptive paragraph (`<p>`) explaining the laundry service.
- An image container with an `<img>` element to display the service image.
- A services section with an unordered list (`<ul>`) listing the offered services.
- A price table (`<table>`) showing service names and costs.
- A footer section with a simple booking form containing text fields and a submit button.

## HTML structure explained

1. `<!DOCTYPE html>`
   - Defines the document as HTML5.

2. `<html lang="en">`
   - Sets the page language to English.

3. `<head>`
   - Contains metadata, character encoding, viewport settings, title, and inline CSS styles.

4. `<body>`
   - Contains all visible content:
     - `h1` page title
     - `p` service description
     - `img` service image
     - `ul` list of services
     - `table` price list
     - `footer` booking fields and button

## CSS details

The inline styles define:

- `h1` centering, top margin, and underline text decoration.
- `.P1` paragraph font size and spacing.
- `img` height, width, and rounded corners.
- `table`, `th`, and `td` borders.
- `footer` text centering.
- `.Book` underlined heading style.

## Notes

- Some CSS rules are commented out, including a reset block and a `.List` alignment style.
- The booking form fields are present but do not currently submit to a server.
- To make the form functional, you can add a `<form>` element with an `action` and `method`.

## How to use

1. Open `index.html` in a browser.
2. Verify that `laundry.png` is located in the same folder, otherwise the image will not appear.
3. Optionally update the text, prices, or styling in `index.html`.

## Improvements

Possible next steps:

- Move styles into a separate `styles.css` file.
- Add a real form submission handler with JavaScript or backend support.
- Make the layout responsive for smaller screens.

