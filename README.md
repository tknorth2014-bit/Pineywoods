# Pineywoods Automotive Website

Static, mobile-friendly website for Pineywoods Automotive (5800 US-27, Ocala, FL 34482).

Pages: `index.html`, `services.html`, `vehicles.html`, `reviews.html`, `contact.html`.
Styles live in `css/style.css`, the mobile menu script in `js/main.js`, and photos in `images/`.

No build step. Hosted on Vercel: import this GitHub repo at vercel.com/new with the "Other" framework preset and no build command — every push to `master` redeploys automatically. `vercel.json` turns on clean URLs (`/services` instead of `/services.html`) and caches images, CSS and JS.

To swap a photo, replace the file in `images/` with one of the same name.
