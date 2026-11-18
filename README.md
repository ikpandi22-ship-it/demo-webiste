# Lakshmi Products Store

A responsive React + Vite storefront with Tailwind CSS, Lucide icons, localStorage cart, and WhatsApp order handoff.

## Run locally

```bash
npm install
npm run dev
```

## Build for deployment

```bash
npm run build
```

Deploy the project to Vercel or Netlify using the build command `npm run build` and output directory `dist`.

## Customize

- Replace `src/assets/hero-products.png` and `src/assets/lakshmi-logo.png` to update the supplied hero artwork and logo.
- Edit the `products` array in `src/main.jsx` to update product details, sizes, images, or prices.
- WhatsApp number is configured in the `WA` constant in `src/main.jsx`.
- Product prices are intentionally shown as `Contact for Price`; no prices or certification numbers have been invented.

Product photographs currently use remote Unsplash image URLs as visual placeholders. Replace these with verified product photographs before launch.
