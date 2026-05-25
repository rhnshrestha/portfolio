---
title: "Why I Built My Developer Portfolio with Hugo and PaperMod"
date: 2026-05-24
draft: false
tags: ["Hugo", "JAMstack", "Performance", "Web Development"]
author: "Rohan Shrestha"
ShowToc: true
TocOpen: true
---

As a **Full Stack Engineer**, my daily work frequently revolves around modern JavaScript frameworks like Next.js, Node.js, and massive containerized services. When it came to building my personal developer portfolio, however, I deliberately took a step back and chose **Hugo** with the **PaperMod** theme.

In this article, I want to explore why static site generators (SSGs) remain the gold standard for developer portfolios and how PaperMod combines robust features with lightweight efficiency.

---

### The Power of the JAMstack (JavaScript, APIs, Markup)

For websites that primarily serve informational content—like portfolios, personal blogs, or product documentation—building a dynamic server-rendered app or a massive client-side single page app (SPA) is often overkill. It leads to:
1.  **Bloated JavaScript bundles** that degrade mobile performance.
2.  **Unnecessary server maintenance and costs** (dealing with database connections, server sleep states, etc.).
3.  **Vulnerability vectors** that are simply absent in static structures.

Hugo compiles standard Markdown files into highly optimized HTML, CSS, and minimal JS files in less than a second. This static markup can then be served globally via content delivery networks (CDNs) like Netlify, Vercel, or GitHub Pages.

---

### Why Hugo?

Among static site generators like Jekyll, Eleventy, or Gatsby, **Hugo** stands out for several reasons:

*   **⚡ Extreme Speed:** Written in Go, Hugo is famously fast. It compiles thousands of pages in milliseconds, making local development instantaneous.
*   **🔌 Zero Dependencies:** Unlike Node.js-based SSGs, Hugo compiles down to a single binary. There is no `node_modules` directory, and dependency vulnerabilities are virtually non-existent.
*   **🛠️ Asset Pipeline:** Hugo Extended includes built-in support for processing, minifying, and bundling SCSS/SASS and JS assets out of the box.

---

### The Elegance of PaperMod

For the theme, I chose **PaperMod**, a highly polished, clean, and fast design. Here is what makes it the perfect fit:

1.  **Lightweight & Minimalistic:** It is incredibly fast out of the box, with minimal styling overhead.
2.  **Built-in Dark Mode:** Supports system preferences (`auto`) or manual toggles to shift colors seamlessly.
3.  **Native Search Integration:** It compiles an `index.json` of your site content and utilizes `Fuse.js` to provide instantaneous client-side search without any third-party APIs.
4.  **Profile Mode:** A built-in homepage layout focused on personal branding, social icons, and easy call-to-action buttons.

---

### Customizing the Vibe

While PaperMod looks great out of the box, as engineers we love to inject our own styling footprint. By using Hugo's asset inheritance, we can inject a `custom.css` file into the compilation chain, introducing modern design accents like custom glassmorphic panels, subtle gradients, and enhanced responsive text sizes.

---

### Conclusion

Your portfolio is the first impression you make on prospective clients, hiring managers, and other developers. Choosing a fast, secure, and clean architecture like **Hugo + PaperMod** shows that you understand performance budgets and appreciate clean, functional engineering.

<!-- *How did you build your portfolio? Let me know!* -->
