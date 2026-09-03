# FoodMart

A responsive, static storefront landing page for a fictional grocery brand. The
project is built with plain HTML and CSS and includes product categories,
product cards, promotional banners, customer testimonials, articles, and a
footer newsletter section.

## Features

- Responsive desktop and mobile navigation
- Product category and product-card sections
- Promotional banners and discount badge
- Testimonial and blog/article sections
- Scroll-to-top and scroll-to-footer links
- No build step, framework, or package installation required

## Project structure

```text
FoodMart/
├── assets/image/     # Page images and icons
├── index.html        # Page markup
├── style.css         # Site and responsive styles
├── favicon.ico
└── README.md
```

## Run locally

Open `index.html` in a browser, or use a local static-file server from the
project folder for the most reliable asset loading.

For example, with the VS Code **Live Server** extension, right-click
`index.html` and choose **Open with Live Server**.

## Deploy with GitHub Pages

1. Create a GitHub repository and publish this project with GitHub Desktop.
2. In the repository on GitHub, open **Settings** → **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing `index.html` (normally `main`) and choose the
   repository root (`/`) folder.
5. Save. GitHub will provide the public site URL after deployment completes.

### Important deployment note

This project currently uses several root-relative asset paths such as
`/FoodMart/assets/...` and `/Front_End_Expert/Foodmart/...`. Root-relative
paths can fail on a GitHub Pages project site because the site is hosted under
the repository name. Before publishing, change these URLs in `index.html` and
`style.css` to relative paths, for example:

```html
<link rel="stylesheet" href="style.css">
<img src="assets/image/Apple.png" alt="Sliced red apple">
```

## Technologies

- HTML5
- CSS3

## Author

Ghazaleh Azimi
