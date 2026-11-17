# Constellation website

A static, single-page site that explains the product: the idea, the three agents, a product tour,
the personas, current features and the roadmap.

- `index.html`: the whole site (inline CSS and JS, no build step). Fonts load from Google Fonts.
- `assets/*.jpg`: screenshots of the app running on the built-in **sample company** (Brightleaf Skincare). No real company data.

Preview: open `index.html` in a browser, or `python3 -m http.server 4000`.

To refresh the screenshots, run the frontend without `NEXT_PUBLIC_API_URL` (mock mode), click
"Explore a sample company instead", and capture each view at about 1360x850.
