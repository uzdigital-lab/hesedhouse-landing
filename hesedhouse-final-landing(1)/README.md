# Hesed.house landing page

Static responsive landing page for GitHub Pages. It uses the original product photos supplied by the owner; image files were copied into `assets/` without editing, cropping, recompression, or retouching.

## Included
- Russian-language responsive landing page
- Swipeable product carousel with 5 original photos
- Telegram subscription links using `https://t.me/+ufB0tSRad39mMjgy`
- Meta Pixel ID `1015625544384062`
- Meta `PageView` event and custom `TelegramClick` event with a `placement` parameter for each CTA location

## Publish with GitHub Pages
1. Create a new repository on GitHub, for example `hesedhouse-landing`.
2. Upload **the contents** of this folder (so `index.html` is at repository root; include `assets/`, `favicon.svg`, and this README).
3. In the repository open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then branch `main` and folder `/ (root)`, and save.
5. Wait for GitHub Pages to publish the site. The resulting public URL will appear in the Pages settings.

## Test the pixel
- Open the published site through its public HTTPS URL.
- In Meta Events Manager, use Test Events to check `PageView` and `TelegramClick` after clicking each Telegram link.
- The custom event records a click to the Telegram invite link; it does **not** prove that the visitor completed a channel subscription.

## Important
This is a static site. Keep the Pixel ID public in front-end code as designed by Meta, but never put Meta access tokens, passwords, or other secrets in this repository. The pixel may take a short time to appear in the Events Manager after testing.
