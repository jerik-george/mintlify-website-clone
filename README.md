# Mintlify Website Clone 🌿

Hey! This is my clone of the [Mintlify](https://mintlify.com) website, built as part of my self-learning journey. The goal of this project was to practice writing clean HTML and CSS by recreating a real-world website from scratch — no frameworks, no JavaScript (mostly!), just pure HTML and CSS.

---

## What I Learned 🎓

This project helped me get comfortable with a lot of core web development concepts like:

- Setting up a proper CSS reset and base styles
- Using CSS variables to keep colors consistent across the project
- Building layouts with Flexbox and CSS Grid
- Working with glassmorphism effects using `backdrop-filter`
- Using `mask-image` to create smooth fade out effects on images
- Embedding and working with Google Fonts
- Working with SVGs — both inline and as image tags
- Managing a project with Git — creating branches per section, squash merging, and keeping a clean commit history

---

## Sections Recreated ✅

Here's everything I built out:

- **Navbar** — fixed navigation with logo, nav links, and contact/start buttons
- **Hero Section** — headline, description, glassmorphism email input with button, and platform screenshot with fade effect
- **Trusted By Section** — grid of company logos (Anthropic, Coinbase, Microsoft, Perplexity, Spotify, Notion, PayPal, Lovable)
- **Intelligent Assistant Section** — feature cards for LLMs/MCP, Agent, and Assistant features
- **Enterprise Features Section** — enterprise pitch with feature highlights and a customer story card
- **Customer Stories Section** — story cards for Anthropic, Perplexity, and X with previous/next buttons
- **Final CTA Section** — centered call to action with pricing and quickstart grid
- **Footer** — logo, social links, 5-column links grid, system status, copyright, and dark mode switcher

---

## Fonts Used 🔤

| Font           | Type                                         |
| -------------- | -------------------------------------------- |
| **Inter**      | Google Font — main body font used throughout |
| **Geist Mono** | Google Font — used for labels and subtitles  |

---

## Colors Used 🎨

All colors are defined as CSS variables in `:root` for easy reuse across the project:

| Color                   | Hex         |
| ----------------------- | ----------- |
| Brand green             | `#2ce19a`   |
| Primary text            | `#ffffff`   |
| Muted text              | `#ffffffb3` |
| Main background         | `#08090a`   |
| Card/section background | `#ffffff0d` |
| Border color            | `#ffffff12` |

---

## Tech Stack 🛠️

- HTML5
- CSS3
- Vite (for local dev server)
- Git + GitHub
- Vercel (for deployment)

---

## Live Demo 🌐

👉 [https://mintlify-website-clone-vert.vercel.app/](https://mintlify-website-clone-vert.vercel.app/)

---

## Notes 📝

A few things worth mentioning:

- The navbar scroll effect (transparent to dark on scroll) requires JavaScript, so the navbar stays transparent since JS was out of scope for this project.
- The customer stories card slider buttons are visual only — the actual sliding functionality would need JavaScript.
- The dark mode switcher in the footer is visual only and shows dark mode as selected by default.
- All images and SVGs were exported directly from the Mintlify website for recreation purposes. This project is purely for learning and not for commercial use.

---

_Built with 💪 as part of my self-learning journey into web development._
