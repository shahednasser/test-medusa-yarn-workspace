# Test Storefront Hosting

This is a monorepo containing a Medusa backend and Next.js storefront.

## Structure

- `backend/` - Medusa backend application
- `storefront/` - Next.js storefront application

## Getting Started

### Prerequisites

- Node.js 18+
- Yarn

### Installation

Install all dependencies:

```bash
yarn install
```

### Development

Run both backend and storefront in development mode:

```bash
# Run storefront only
yarn dev

# Run backend only
yarn dev:backend

# Run storefront only
yarn dev:storefront
```

### Build

Build all packages:

```bash
yarn build
```

Or build individually:

```bash
yarn build:backend
yarn build:storefront
```

### Start Production

```bash
# Start storefront
yarn start

# Or individually
yarn start:backend
yarn start:storefront
```

## Workspaces

This monorepo uses Yarn workspaces to manage dependencies across packages. All shared dependencies are hoisted to the root `node_modules`.
