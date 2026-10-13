# DataScaler Product Updates

Static bilingual prototype for the DataScaler product updates page.

## Preview

- Demo: https://product-updates-demo.vercel.app/
- Entry file: `index.html`
- No build step or package installation is required.

Run a local preview:

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Production routes

- English: `/en/product-updates`
- Chinese: `/product-updates`

Add `Product updates / 产品更新` under `Resources / 资源` in both the header and footer.

## Metadata

English:

- Title: `DataScaler Product Updates | New Features & Improvements`
- Description: `Follow the latest DataScaler product updates, including new features, product improvements, integrations, and fixes across the platform.`

Chinese:

- Title: `DataScaler 产品更新｜新功能、优化与版本说明`
- Description: `查看 DataScaler 最新产品更新，了解平台新功能、产品优化、集成能力和问题修复。`

Production implementation should render each language on its own route and add canonical URLs, reciprocal hreflang tags, sitemap entries, and indexable metadata server-side.

## Included behavior

- English and Chinese content switching
- Language-specific product screenshots
- Image lightbox with close button, backdrop click, and Escape support
- Responsive desktop and mobile layouts
- Setup links to the matching English or Chinese documentation
