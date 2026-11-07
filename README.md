# FoodBridge — Good food deserves another table

FoodBridge is a responsive, one-page social-impact homepage concept for connecting surplus food donors with NGOs and local communities.

> **Brand promise:** Share more. Waste less.

## Experience

- Editorial hero section with a clear food-donation call to action
- Problem and solution storytelling
- Four-step donation journey
- Features for food donation, NGO partnerships, pickup coordination and community participation
- Impact section designed to display verified metrics as the platform grows
- Clearly labelled illustrative community stories
- Interactive donor, volunteer and partner forms
- FAQ accordion, mobile navigation and responsive layouts

## Tech stack

- React 18 + TypeScript
- Vite
- Tailwind CSS with a custom responsive CSS design system
- Framer Motion for motion and transitions
- Lucide React for iconography

## Run locally

```bash
npm install
npm run dev
```

Vite prints the local development URL (usually `http://localhost:5173`).

## Production build

```bash
npm run build
npm run preview
```

The production output is generated in `dist/`.

## Deploy on Vercel

1. Import this GitHub repository into Vercel.
2. Select **Vite** as the framework preset.
3. Set the build command to `npm run build`.
4. Set the output directory to `dist`.
5. Deploy.

## Deploy on Render

Create a **Static Site** from this repository.

- Build command: `npm install && npm run build`
- Publish directory: `dist`

## Demo interaction and data integrity

The donation, volunteer and partner forms validate required fields and display a confirmation state. They are frontend demonstrations only: they do not transmit data, create real pickup requests or contact an operations team. Connect a secure backend or form service before collecting real requests.

Impact totals are intentionally not fabricated. The impact section explains the intended outcomes and reserves numerical reporting for verified donations and deliveries. Community stories are explicitly labelled illustrative examples.

## Assets

Photography is loaded from Unsplash and fonts (DM Sans and Manrope) from Google Fonts. An internet connection is required for these external assets.
