# LaSALe FHUI Website

Landing page for Law Student Association for Legal Practice, Faculty of Law, Universitas Indonesia.

## Tech Stack
- **Astro 5.0** - Static site generation
- **Tailwind CSS v4** - Utility-first styling
- **@tailwindcss/vite** - Vite integration

## Quick Start

```bash
# Install dependencies
npm install

# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment to Vercel

1. Push to GitHub
2. Import project on Vercel
3. Framework preset: Astro
4. Deploy

Or use Vercel CLI:
```bash
npx vercel
```

## Project Structure
```
src/
├── components/    # Page sections
├── layouts/       # Layout wrapper
├── pages/         # Routes
└── styles/        # Global CSS
```

## Design System
- Colors: Cornsilk, Vanilla, Canary Yellow, Dusty Mauve, Egyptian Blue
- Fonts: Instrument Sans, Jost, Pinyon Script
- Animations: CSS-only with Intersection Observer for scroll effects