# Jellyfish GTM Playbook

Internal positioning and go-to-market playbook for Jellyfish, as a single static page.

## Tabs

**Playbook**
- **GTM Flow**: 3 GTM campaigns (Adopt, Transform, Thrive), each from personas to campaign landing page, pitch deck and demo
- **JF Messaging Manifesto**: the narrative, journeys, proof, personas and messaging rules
- **Killer Use Cases**: outreach, hook, discovery questions, pitch and demo blocks per journey

**December (Dec 1 launch)**
- **Announcement Blog**: "We Built the Category That Measures Engineering Productivity. AI Agents Made It Obsolete."
- **Jelly AI**: platform page with a left-to-right marketecture diagram and a filterable changelog from #releases
- **NAV Structure**: interactive mock of the new jellyfish.co Platform mega menu
- **Blog: AI Spend <> Work**: placeholder (WIP)
- **How We Built ShipMate**: draft engineering blog for Nathan
- **Pitch Deck**: First Call Deck, slide by slide
- **CLP pages**: landing pages for Maximize your AI coding agents’ ROI, Run the AI-native SDLC, and Human + agent eng. teams that move the business

## Files

```
index.html                  the whole site (HTML, CSS and JS inline)
slides/s-01.jpg … s-27.jpg  First Call Deck slide images
img/session-unit-of-work.gif  animated diagram used in the blog
.nojekyll                   tells GitHub Pages to serve files as-is
```

## Publish with GitHub Pages

1. Push these files to the root of a repo (for example `jf-messaging-pitch`).
2. In the repo, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
3. The site appears at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

To preview locally, open `index.html` in a browser.

## Notes

- Internal only: contains pre-GA features (Agent Observatory), draft case-study material and internal release notes. Keep the repo private, or use a private Pages site if your GitHub plan supports it.
- Links to the First Call Deck and manifesto docs point to claude.ai and only open for people in the Jellyfish org.
