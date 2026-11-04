# Rick and Morty Character Search — Hosting Assignment

A Vue 3 character search deployed to GitHub Pages and Surge.

## Run locally

```sh
npm ci
npm run dev
```

## Deploy to GitHub Pages

The GitHub Actions workflow builds and deploys the site whenever a commit is pushed to `main`. The Vite base path is set for this repository in the workflow.

## Deploy to Surge

```sh
npm run build
npx surge dist <your-domain>.surge.sh
```
