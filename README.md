# Velocity Loop — deploy

Static single-page site, self-contained (all fonts, styles, images and scripts inlined into `public/index.html`).

## Railway

1. Push this folder to a GitHub repo (or drag it into a new Railway project).
2. Railway detects Node and runs `npm start`.
3. It binds to `process.env.PORT` automatically. No build step, no dependencies.

## Local

    node server.js
    # http://localhost:3000

## Editing

`public/index.html` is compiled output — do not hand-edit it. Change the source design and re-export.

## If you'd rather have a React project

This build is framework-free on purpose so it deploys with zero config. Ask and I can produce a React/Vite component handoff instead — same markup, split into components, with the animation logic as a hook.
# AI-Agency-Website
