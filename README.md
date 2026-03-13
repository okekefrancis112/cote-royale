# Cote Royale

A premium fragrance e-commerce website built with Next.js 15, Prismic CMS, and GSAP animations.

## Overview

A beautifully animated fragrance brand website featuring dynamic content management through Prismic, smooth GSAP animations, and modern Next.js App Router architecture.

## Features

- **Prismic CMS** — Headless content management for fragrances and pages
- **GSAP Animations** — Smooth, professional scroll and page animations
- **Next.js 15** — App Router with Turbopack for fast development
- **View Transitions** — Seamless page transitions
- **Custom Slice Types** — Fragrance and homepage content models

## Tech Stack

- **Next.js** 15 — React framework
- **Prismic** — Headless CMS
- **GSAP** — Animation library
- **React** 19
- **TypeScript**
- **Tailwind CSS** — Styling

## Getting Started

```bash
git clone https://github.com/okekefrancis112/cote-royale.git
cd cote-royale
npm install
npm run dev
```

### Prismic Slice Machine

```bash
npm run slicemachine
```

## Project Structure

```
├── app/                     # Next.js App Router pages
├── components/              # React components
├── customtypes/             # Prismic content models
│   ├── fragrance/           # Fragrance type
│   ├── homepage/            # Homepage type
│   └── settings/            # Site settings
├── documents/               # Prismic documents
└── package.json
```

## License

MIT
