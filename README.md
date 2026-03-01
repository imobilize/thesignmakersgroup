# The Sign Makers Group

Website for The Sign Makers Group — a leading sign manufacturing company.

**Live site:** [www.thesignmakersgroup.com](https://www.thesignmakersgroup.com)

---

## Tech Stack

| Tool | Purpose |
|---|---|
| [Hugo](https://gohugo.io/) v0.156.0 | Static site generator |
| [Tella](https://github.com/opera7133/tella) | Hugo theme |
| [Tailwind CSS](https://tailwindcss.com/) v4 | Utility-first CSS framework |
| [DaisyUI](https://daisyui.com/) | Tailwind component library |
| [Alpine.js](https://alpinejs.dev/) | Lightweight JS framework |
| [Netlify](https://www.netlify.com/) | Hosting and deployment |

---

## Prerequisites

- [Hugo](https://gohugo.io/installation/) v0.156.0 or later (extended version)
- [Node.js](https://nodejs.org/) v18 or later
- [npm](https://www.npmjs.com/)

---

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd thesignmakersgroup
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

---

## Running Locally

Start the development server (runs Hugo and Tailwind CSS in watch mode concurrently):

```bash
npm start
```

The site will be available at [http://localhost:1313](http://localhost:1313).

---

## Building for Production

```bash
npm run build
```

The generated site will be output to the `public/` directory.

---

## Deployment

The site is deployed automatically via [Netlify](https://www.netlify.com/) on every push to the main branch. Build settings are configured in [`netlify.toml`](netlify.toml).
