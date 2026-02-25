# Compiler Construction Notes

NOTE: This is partly created using AI. All the content for the blog  is human written (and hence prone to error) while the site setup was created using AI Agents.

This repository contains a Jekyll-based site that hosts notes, tutorials, and example material about compiler construction. The site is prepared for static site generation and includes posts, pages, and static assets.

Key contents
- `_posts/`: blog-like posts, including `2026-02-22-intro-to-compilers.md`.
- `compilers/`: exported HTML for specific compiler topics.
- `assets/`: CSS, JS, images used by the site.
- `script/`: helper scripts to build, serve, and release the site.

Quick start (local)

Prerequisites:
- Ruby (for Jekyll) and Bundler
- Node/npm (for frontend tooling if you modify assets)

Typical local workflow:

1. Install Ruby gems:

```bash
bundle install
```

2. Start the local server (development):

```bash
./script/server
# or
bundle exec jekyll serve
```

3. Build the site for production:

```bash
./script/build
# or
bundle exec jekyll build
```

Project scripts
- `script/server` — run a local dev server
- `script/build` — build the static site
- `script/release` — release/deploy helper

License

This project includes a `LICENSE.md` file at the repository root. Please review it for license details.

Contact / Author - Prajesh - pg2973@nyu.edu

See repository metadata and commit history for the primary maintainer contact information.

Enjoy exploring compiler construction!


