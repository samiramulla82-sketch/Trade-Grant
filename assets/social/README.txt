Fallback social image

This repository uses a dynamic Unsplash image as the social preview fallback. The image URL used in the site metadata is:

https://source.unsplash.com/1200x630/?trade

Notes:
- Unsplash serves a JPG at the specified dimensions (1200x630) matching common Open Graph/Twitter expectations.
- Because this is a dynamic endpoint, the exact image may change over time or between requests.
- If you prefer a stable, versioned image, download an image from Unsplash (or another provider), add it to assets/social/ (for example assets/social/social-preview.png), and update the meta tags in index.html to point to the local asset path.
