# FIB Landing Page

A Next.js landing page with Vercel Speed Insights integration.

## Features

- ⚡ Next.js 14 with App Router
- 📊 Vercel Speed Insights for performance monitoring
- 🎨 Tailwind CSS for styling
- 📝 TypeScript support

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Speed Insights

This project includes Vercel Speed Insights to monitor real user performance metrics. The `<SpeedInsights />` component is automatically included in the root layout (`app/layout.tsx`).

To view metrics:
1. Deploy to Vercel
2. Visit your site to generate traffic
3. Check the Speed Insights dashboard in your Vercel project

## Deployment

Deploy to Vercel with one click:

```bash
vercel deploy
```

Or connect your Git repository to Vercel for automatic deployments.
