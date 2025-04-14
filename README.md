# Modern.js SSR Deployment Example

This is a SSR (Server-Side Rendering) application example project built with the Modern.js framework, designed to showcase different deployment approaches. The project supports the following three deployment methods:

- Node.js server deployment
- Vercel platform deployment
- Netlify platform deployment

## Project Features

- Built with the Modern.js framework
- Uses SSR (Server-Side Rendering) technology to enhance performance and SEO
- Supports multiple deployment platforms
- Built with React 18 for the user interface
- Uses TypeScript for type safety
- Uses Rspack as the default build tool (can be switched to webpack)

## Prerequisites

- Node.js >= 16.18.1
- pnpm package manager

## Getting Started

### Install Dependencies

```bash
pnpm install
```

### Local Development

Start the development server:

```bash
pnpm dev
```

### Build for Production

```bash
pnpm build
```

### Preview Production Build Locally

```bash
pnpm serve
```

### Add New Features or Entries

```bash
pnpm new
```

## Deployment Guide

### Node.js Deployment

1. Build the application:
   ```bash
   pnpm build
   ```

2. Start the Node.js server:
   ```bash
   pnpm start
   ```

### Vercel Deployment

The project includes a `vercel.json` configuration file, allowing direct deployment to the Vercel platform:

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Deploy to Vercel:
   ```bash
   vercel
   ```

Alternatively, connect your GitHub repository to Vercel for automatic deployment.

### Netlify Deployment

The project includes a `netlify.toml` configuration file, allowing direct deployment to the Netlify platform:

1. Install Netlify CLI:
   ```bash
   npm i -g netlify-cli
   ```

2. Deploy to Netlify:
   ```bash
   netlify deploy
   ```

Alternatively, connect your GitHub repository to Netlify for automatic deployment.

## Project Structure

```
/
├── src/                  # Source code directory
│   ├── routes/           # Route components
│   ├── modern.runtime.ts # Runtime configuration
├── modern.config.ts      # Modern.js configuration file
├── vercel.json           # Vercel deployment configuration
├── netlify.toml          # Netlify deployment configuration
├── package.json          # Project dependencies and scripts
└── tsconfig.json         # TypeScript configuration
```

## Other Commands

- Code linting: `pnpm lint`
- Reset dependencies: `pnpm reset`
- Upgrade dependencies: `pnpm upgrade`

## Learn More

- [Modern.js Documentation](https://modernjs.dev/en)
- [Modern.js GitHub Repository](https://github.com/web-infra-dev/modern.js)
