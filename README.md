# TikTok Growth Studio

A responsive creator workspace for planning TikTok content, generating content ideas, recording performance metrics, and exporting workspace data. Includes an installable Android PWA.

## Current scope

- Content planner and publishing workflow tracker
- Local template-based content idea generation
- Manually recorded analytics and engagement calculations
- Responsive dashboard, dark mode, and PWA shell
- Node.js built-in HTTP server and JSON persistence
- Basic API tests

This project does **not** fake engagement or claim to publish to TikTok. Official TikTok OAuth, real video publishing, media upload, and live analytics still require approved developer credentials and implementation.

## Run

Requires Node.js 20+.

```sh
npm test
npm start
```

Open `http://127.0.0.1:8080`.

The full initial project bundle is available in the downloadable ZIP linked in the project's release/commit artifacts when uploaded. See TikTok's [Content Posting API](https://developers.tiktok.com/docs/en/content-posting-api-reference-direct-post) and [Getting Started](https://developers.tiktok.com/docs/en/content-posting-api-get-started) docs before implementing official publishing.