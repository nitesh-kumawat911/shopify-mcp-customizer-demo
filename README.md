# MCP-Powered Shopify Customizer — Live Demo

An interactive demo of a **content customizer that maps to a live storefront**. Edit the brand name, hero copy, accent colour, fonts, sections, and featured products on the left — and watch a premium storefront update **instantly** on the right.

It shows the idea behind a Shopify MCP (Model Context Protocol) workflow: a merchant manages content from a dashboard, and the changes flow straight through to the frontend — no developer needed for everyday content and layout edits.

## Live demo

Open `index.html` in any browser. It's a single self-contained file — no build step, no dependencies.

To host it for free, push this repo to GitHub and enable **GitHub Pages** (Settings → Pages → Branch: `main` → `/root`). Your live link will be:
`https://nitesh-kumawat911.github.io/shopify-mcp-customizer-demo/`

## What you can edit

- Announcement bar text + visibility
- Brand name
- Hero eyebrow, headline, subtext, and call-to-action
- Accent colour, heading font, and background theme
- Show/hide the Category, Featured Products, and Customer Quote sections
- Featured product names and prices

Every change triggers a sync pulse on the central **MCP** node and reflects live in the storefront — the same dashboard-to-frontend mapping a real MCP bridge performs.

## How it works

This is a **front-end demo** of the concept. The "MCP bridge" here is illustrated with client-side state binding (vanilla JavaScript) so the idea is easy to see and share. In a production setup, that bridge connects the customizer to a Shopify store through the Model Context Protocol, syncing real theme settings, metafields, and content.

Built with plain HTML, CSS, and JavaScript — no frameworks — so it loads fast and is easy to read.

## Tech

`HTML` · `CSS` (custom properties for live theming) · `Vanilla JS` · responsive · reduced-motion friendly

## License

MIT — free to use and adapt.

---

Built by **Nitesh Kumawat** — Shopify & front-end developer specialising in AI-assisted eCommerce (Shopify MCP, Claude API, n8n).
Open to freelance / remote work: niteshkumawat911@gmail.com
