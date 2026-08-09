# Hopper — website

The public site for **Hopper**, a Windows desktop app that watches folders on
your PC and uploads videos to your TikTok drafts at the best time to post.

These pages exist mainly to satisfy TikTok's developer app requirements, which
demand a public website, a Terms of Service URL and a Privacy Policy URL.

| Page | Purpose |
|---|---|
| `index.html` | What Hopper is and how it works |
| `terms.html` | Terms of Service |
| `privacy.html` | Privacy Policy |
| `contact.html` | Contact form |

Served by GitHub Pages from the repository root. Plain static HTML — no build
step, no dependencies. Edit a file, commit, push; Pages redeploys on its own.

The logo is embedded directly in each page as a data URI, so the pages render
correctly whether they are served, opened from disk, or previewed in a tool
that does not resolve relative paths.

## Before the contact form works

`contact.html` posts to [Web3Forms](https://web3forms.com/). Get a free access
key there — you give them the address messages should be forwarded to, and it
never appears on this site — then replace `PASTE_WEB3FORMS_ACCESS_KEY_HERE` in
`contact.html` with the key.
