# Tuple's landing page

## Developing

1. Install deps: `yarn`

2. Watch for changes and recompile: `webpack --watch`

Webpack will watch `/src/styles.css` and `/tailwind.js` and rebuild your stylesheet on every change. (Sometimes, or it will crash because JavaScript is a steaming pile of shit.)

## Deploy

The site is deployed automatically to Netlify.

Configure that here: https://app.netlify.com/sites/tuple-landing-page.

There is currently no build command that's run on deploy, so make sure that you've built locally, and that `dist/index.html` has your updates.
