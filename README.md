# Offline Free-Camera Roaming in WoW Classic

A single-page guide on roaming World of Warcraft Classic with a free camera, no
user interface, and no character to walk around, entirely offline and without
touching your game account.

**🔗 Live:** https://jacoblbagent.github.io/wow-offline-camera-guide/

## What it covers

- Why the offline approach carries no account risk (anti-cheat only observes a
  running, connected game client)
- The simplest working setup: `wow.export`'s built-in 3D world viewer reading
  your local client data
- Free-camera movement with no UI and no character
- Recording the flythrough
- Graduating to authored cinematic camera paths via the Blender pipeline
- Alternatives (Noggit, self-hosted wow.tools) and the do/don't list

## Stack

- Single-file static HTML (`index.html`), inline CSS, no build step, no JS
- Hosted on GitHub Pages (main branch root, `.nojekyll`)

## Run / edit

```bash
# open locally
xdg-open index.html
```

Push to `main` and GitHub Pages redeploys automatically.

## Deploy

Pages is enabled for the `main` branch root. Bump `index.html`, commit, push.
