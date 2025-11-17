This is a [Next.js](https://nextjs.org) project bootstrapped with :

```bash
git clone git@github.com:jlpek17/learnJsAndReact.git
echo "# learnJsAndReact" > README.md

npx create-next-app@latest .
```

- **nos typescript => JavaScript**
- **ESLint enabled**
- **React Compiler**
- **No Tailwind CSS**
- **Code in `/src`**
- **Pages Router (no App Router)**
- **Default import alias (`@/`)**

> React est automatiquement installé avec Next.js. Les dépendances `react` et `react-dom` sont ajoutées lors de l'initialisation du projet

## Getting Started

Check node version and nstall nodeversion files :
```bash
fnm ls
```

Install the dependencies:

```bash
npm cache clean --force
npm install --registry=https://registry.npmjs.org/ --verbose
or
npm update --registry=https://registry.npmjs.org/ --verbose
```

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/pages/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.
