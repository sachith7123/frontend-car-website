# VELORE — Luxury Automobile Collection

A responsive, multi-page luxury car showroom and marketplace frontend built with HTML, CSS and vanilla JavaScript.

## Run locally

Open `index.html` in a current browser, or serve this folder with any static HTTP server. For example, from this directory:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`. There is no build step, backend, account system or payment service.

## Pages

- `index.html` — cinematic home, featured vehicles, marques, categories and newsletter demo.
- `cars.html` — searchable collection with manufacturer, type, powertrain, price and horsepower filters, sorting, list/grid view and saved cars.
- `car-details.html?id=revuelto` — dynamic vehicle details, image gallery, specifications and enquiry demo. Unknown IDs show a fallback page.
- `brands.html` — editorial directory for 12 automotive marques.
- `sell.html` — multi-step vehicle listing preview; submitted demo listings are saved in browser localStorage only.
- `about.html` — VELORE story, philosophy and sample team profiles.
- `contact.html` — contact form demo and FAQ accordion.

## Assets and behavior

Vehicle photography is loaded from Unsplash image URLs; Google Fonts provides Manrope and DM Sans. Browser fallbacks are included for failed vehicle images. Internet access is needed for these external assets. Sample vehicle prices and testimonials are illustrative. Wishlist entries and seller listing demos use localStorage. Contact, newsletter and enquiry forms validate in the browser and do not submit to a server. All page behavior lives in `js/app.js`, and catalogue content is centralized in `js/data.js`.
