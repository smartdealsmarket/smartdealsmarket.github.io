# Smart Deals Market

Marketing landing page for **Smart Deals Market** — Potomac Mills Mall's premier liquidation outlet in Woodbridge, VA.

## Deploy

### GitHub Pages
1. Create a new repo and push these two files.
2. Go to **Settings → Pages**.
3. Set **Source** to `Deploy from a branch` → `main` → `/ (root)`.
4. Save. Your site will be live at `https://<username>.github.io/<repo>/`.

### Netlify / Vercel
Just drag-and-drop the folder, or connect the repo. No build step needed.

## What's inside

- **`index.html`** — the entire site. React 19 + Babel in-browser, Tailwind-style CSS inlined, Google Maps embed, Instagram links.
- No npm install, no bundler, no config required.

## Edit content

Open `index.html` and search for:
- `RULES` — the three "store rules" cards
- `INVENTORY` — the three inventory category cards
- `SOCIAL` — the Instagram-style feed tiles
- `HOURS` — store hours
- Address/phone — search for `2700 Potomac` and `571` to update
- Instagram handle — search for `smartdealsmarket_`

## Analytics (optional)

A PostHog snippet is included at the bottom of the HTML, commented out. Replace
`phc_YOUR_PROJECT_KEY` with your own PostHog project key and uncomment it to
enable analytics.

## Design system

| Token | Value |
|---|---|
| Background | `#0B0D10` |
| Primary (orange) | `#FF5500` |
| Primary hover | `#E04800` |
| Accent (cyan) | `#00E5FF` |
| Success (green) | `#10B981` |
| Card | `#181C24` |
| Display font | Outfit |
| Body font | Plus Jakarta Sans |
| Mono font | JetBrains Mono |

## Optional: enable PostHog analytics

1. Sign up at https://posthog.com
2. Create a project → copy the `phc_...` project API key
3. Open `index.html`, scroll to the bottom
4. Uncomment the `<script>` block marked "OPTIONAL — PostHog analytics"
5. Replace `phc_YOUR_PROJECT_KEY` with your key
6. Deploy
