# Hello World • Hyrax & Redfoot

A friendly, modern 3-page website built for easy testing and deployment on **Vercel**.

**Theme**: Hello World  
**Pages**: Home, About (Hyrax + Red-footed Tortoise), Sign the Guestbook

## Features
- Beautiful warm, nature-inspired design with Geist font
- **Meet the Consuls** — two hover-lift ambassador cards (Hyrax & Redfoot) with distinct button hover styles
- Multiple **email buttons** that open a small, polished “New Message” modal window
  - Prefilled `To: info@hyrax-example.com`
  - Subject: `Hello World`
  - Optional message body
  - “Open in Mail” triggers real `mailto:` link + demo send mode
- Fully interactive **guestbook** (`/sign`) powered by localStorage
  - Add your own greetings (name + message + optional location)
  - 4 seeded demo comments on first visit
  - Delete individual entries or clear all
- Fully responsive, accessible, and static-export friendly
- Zero external API calls — perfect for quick Vercel previews

## Quick Start (Local)

```bash
cd hello-world-site
npm install
npm run dev
```

Open http://localhost:3000

## Deploy to Vercel (one click)

1. Push this folder to a GitHub/GitLab repo, **or**
2. From the project root run:

```bash
npm run build          # verify it builds cleanly
npx vercel             # follow the prompts (first time creates new project)
```

Or use the Vercel dashboard → “Add New Project” → import the repo.

The site is 100% static and deploys instantly.

## Pages

| Route   | Purpose                              |
|---------|--------------------------------------|
| `/`     | Home + Hero + Meet the Consuls       |
| `/about`| Detailed stories of both animals     |
| `/sign` | Guestbook — leave & view comments    |

## Email Buttons

Any “Send a Hello” / “Greet the Consul” opens the small centered email compose window.  
Clicking **Open in Mail** launches your default email client with everything pre-filled.

---

Made as a clean test site for Vercel. Enjoy saying hello! 🐢🪨

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
