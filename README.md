# PRIME 2025

> Participatory Research into Inclusion, Migration and Equity (PRIME)

This is the source code for the official website of the PRIME 2025 research project. PRIME explores how to foster more inclusive and equitable societies by focusing on the lived experiences of migrant and minoritized communities.

Built using [Hugo](https://gohugo.io/), a fast and modern static site generator.

---

## 🌐 Project Overview

PRIME is a participatory research initiative that:

- Investigates inclusion and equity in public services.
- Engages with communities across sectors (housing, healthcare, education, creative industries).
- Promotes knowledge sharing and co-creation between academics, communities, and policymakers.

The website showcases:

- Current and past team members.
- Outputs such as publications, videos, and events.
- Opportunities for collaboration and dissemination.

---

## 🚀 Live Site

> 🔗 [https://www.primecommunities.online/](https://www.primecommunities.online/)  

---

## 📁 Project Structure

This Hugo site uses a modular structure with custom layouts and content types.

```
prime-2025/
├── content/           # Content files (team, outputs, etc.)
├── layouts/           # Custom Hugo templates and partials
├── static/            # Static assets (images, CSS, favicon, etc.)
├── themes/            # Theme used or custom overrides
├── config.toml        # Site configuration
├── README.md          # Project documentation
└── ...
```

Key content sections:

- `content/team/`: Current and past team members (with support for `alumni: true` flag).
- `content/outputs/`: Project outputs such as publications, videos, and media.
- `layouts/`: Custom layouts for summary, listing, filtering, and detail pages.

---

## 🛠️ Getting Started

### Prerequisites

- [Hugo](https://gohugo.io/getting-started/installing/) (>= v0.92)
- Git

### Development

```bash
git clone https://github.com/thePrimeProject/prime-2025.git
cd prime-2025
hugo server
```

Visit `http://localhost:1313` to preview the site locally.

---

## 🛎️ Deployment (GitHub Pages)

This site is deployed via [GitHub Pages](https://pages.github.com/). To deploy manually:

```bash
hugo --minify
cd public
git init
git remote add origin https://github.com/thePrimeProject/prime-2025.git
git add .
git commit -m "Deploy site"
git push -f origin gh-pages
```

Or use GitHub Actions with `peaceiris/actions-gh-pages`.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE) or institutional equivalent. Please check with the PRIME project team for reuse permissions of research content.

---

## 🙌 Contributing

We welcome collaboration!

If you'd like to contribute to the site (bug fixes, content updates, etc.):


1. Fork the repo
2. Create a new branch: `git checkout -b feature/my-update`
3. Commit your changes
4. Submit a Pull Request

---

## 👥 Team

Developed and maintained by the PRIME 2025 team.