# shadcn/ui Connect Demo

A Next.js project with shadcn/ui components, ready for Figma Code Connect integration.

## Features

- **Next.js 15** with App Router
- **TypeScript** for type safety
- **Tailwind CSS** for styling
- **shadcn/ui** component library
- **Figma Code Connect** ready

## Components

- `Button` - A customizable button component with multiple variants and sizes

## Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the result.

## Figma Code Connect

This project is configured for Figma Code Connect integration. The `Button` component is available at:

```
src/components/ui/button.tsx
```

## Project Structure

```
src/
├── app/                 # Next.js App Router
│   ├── globals.css     # Global styles with CSS variables
│   ├── layout.tsx      # Root layout
│   └── page.tsx        # Home page
├── components/
│   └── ui/
│       └── button.tsx  # Button component
└── lib/
    └── utils.ts        # Utility functions
```