# Made Nearby

An interactive front-end prototype for discovering neighbourhood makers, comparing services and rates, and following custom-work requests.

## Run the prototype

Open `index.html` in a modern browser. The page is a self-contained HTML, CSS, and JavaScript demo; no build step is required. Internet access is used for the credited Unsplash photos and Google Maps links.

Use the built-in **Customer demo** and **Maker demo** buttons to explore the two roles.

## Prototype features

- Maker discovery by craft, search, price range, rating, reviews, distance, and approximate queue time
- Individual maker profiles with services, starting rates, reviews, contact links, and map search
- Order requests, maker quotes, status tracking, collection, and post-collection reviews
- A rotating featured-photo carousel and animated queue illustration
- Local demo controls for maker profile review, shop logo, and work-photo previews

## Demo limitations

This is a browser-only prototype. Accounts and activity use local browser storage; sign-in is not secure production authentication, and data does not sync between devices. KYC is a local review-request mockup and does not verify identity. Uploaded image previews stay in the browser. Firebase is not connected; for a live app, upload images to Firebase Storage and keep image URLs in Firestore. Map locations are illustrative until makers add real addresses or coordinates. Prices and ready times are estimates that makers must confirm.
