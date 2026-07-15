# Roze Health Premium Astro Site — v4

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Cloudflare Pages settings:
- Framework preset: Astro
- Build command: `npm run build`
- Output directory: `dist`

## Jane links

The Jane booking and patient portal URLs are set in `src/pages/index.astro`:

```js
const bookingUrl = "https://rozehealth.janeapp.com/";
const portalUrl = "https://rozehealth.janeapp.com/";
```

## Treatment sections

- Dysport®
- Dermal Fillers: Lip, Cheek, Chin, and Jawline
- Microneedling: Texture, Fine Lines, Acne Scars, and Skin Quality

## Main additions in v4

- New premium Microneedling section with an on-brand CSS treatment visual
- Microneedling link in the primary navigation
- Expanded treatment FAQ for Dysport®, fillers, and microneedling
- Updated hero and SEO copy to include skin-renewal treatments
- Corrected the Astro site URL to `https://www.roze-health.ca`
- Responsive styling and reveal animations retained
