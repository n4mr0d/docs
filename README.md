# DProdz Marketing Site

Modern marketing website for **DProdz**, an Algerian digital innovation company. Built with [Astro](https://astro.build/) and
a handcrafted component system to highlight each service offering.

## Getting Started

1. Install dependencies (requires Node 18+):

   ```bash
   npm install
   ```

2. Run the development server:

   ```bash
   npm run dev
   ```

3. Build for production:

   ```bash
   npm run build
   ```

4. Preview the production build locally:

   ```bash
   npm run preview
   ```

## Project Structure

```
├── public/               # Static assets
├── src/
│   ├── components/       # UI components for each section
│   ├── layouts/          # Base layout wrapping every page
│   ├── pages/            # Astro pages (entry points)
│   └── styles/           # Global styling
├── astro.config.mjs      # Astro configuration
├── package.json          # Scripts and dependencies
└── tsconfig.json         # TypeScript settings
```

## Customisation

- Update content inside `src/components` to adjust copy or imagery.
- Replace image URLs with local assets by adding files under `public/`.
- Modify theme colors and spacing within `src/styles/global.css`.

## Deployment

The site can be deployed to any static host that supports Astro builds, such as Vercel, Netlify, GitHub Pages, or a custom
hosting provider.
