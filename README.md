# Arcana — FRIDAY Developer Knowledge Hub

Mobile-first React/Vite reconstruction of the FRIDAY learning hub.

## Quick start

Requires Node.js 20.19+ or 22.12+.

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

## GitHub upload

Upload the **contents** of this folder to the root of `misssadiesink/Arcana`, not the outer `arcana` folder. Use GitHub → Add file → Upload files, or clone and push.

## Deployment

On Netlify or Vercel, import the GitHub repository. Framework: Vite; build command: `npm run build`; output directory: `dist`. This app uses hash-based navigation, so deep links do not require server rewrite rules.

## Where to edit

- `src/content.js` — learning modules, companies, starter interview questions
- `src/main.jsx` — app navigation and functionality
- `src/style.css` — mobile-first visual design
- `index.html` — metadata

## Recovery limitations

This is a **new reconstruction**, not the original ChatGPT Work source code. It preserves the published topic structure, but not the full original lesson wording, complete question database, user data, or original deployment. The initial content is a concise learning foundation; deeper lessons should be expanded iteratively. The starter question bank contains 22 questions, not the previously claimed 227.

Bookmarks, completion and theme use browser localStorage, so they are not synced across devices. No authentication, backend, analytics or cloud storage is included.
