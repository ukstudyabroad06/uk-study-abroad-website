UK Study Abroad Website - Cloudflare Workers

This package restores the original Next.js/vinext application source, including:
- app/ (homepage and pages)
- components/
- public/
- worker/index.ts
- build/sites-vite-plugin.ts
- scripts/
- .openai/hosting.json
- original vinext/Cloudflare Vite configuration

IMPORTANT:
1. Extract this ZIP.
2. Upload/commit the CONTENTS of the uk-study-abroad-website folder to the ROOT of the GitHub repository.
3. Do not upload the outer folder itself as the only item.
4. Cloudflare Workers Builds should keep Root directory as /.
5. Build command: npm run build
6. Deploy command: npx wrangler deploy
7. After deployment, test the workers.dev URL before connecting a custom domain.
