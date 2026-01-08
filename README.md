# Darkmoon Wiki

This is the Darkmoon wiki.

It uses [mdBook](https://github.com/rust-lang/mdBook) to build the book. Docs for that can be found [here](https://rust-lang.github.io/mdBook/).

On merges to main, it deploys to GitHub pages and Cloudflare pages
On PRs, it pushes to cloudflare pages (for previewing); check the deployment notes in the PRs.

Pages URL: https://logikal.github.io/darkmoonwiki/
Cloudflare URL: https://darkmoonwiki.pages.dev/


TODO:

- [x] GitHub Actions for pages deployment
- [ ] Deploy to custom domain for Darkmoon branding (wiki.darkmoon3d.com? darkmoon.wiki?)
- [ ] Add more content
  - [ ] Migrate print profiles
