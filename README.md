# Hi, I'm Alireza Heidari

Senior Software Engineer based in Freiburg, Germany, with 6+ years of experience in full-stack product engineering. I build the shared components, APIs and data layers a product runs on, and move old code onto them in small, measured steps.

Since August 2022 I have worked as a Software Engineer on [Galaxy](https://galaxyproject.org) at the University of Freiburg. Galaxy is an open-source data analysis platform with 650,000+ registered users on its public services in Europe, the US and Australia. I have been one of its core committers since August 2024. Before that I was an early hire at a genomics startup, where I owned all engineering end to end.

## Recent work at Galaxy

- Drove the Vue 3 migration of the Galaxy client, including browser-test triage that took Selenium and Playwright from 142 failures to zero.
- Designed the shared table component (GTable) and moved about ten product areas onto it.
- Designed the tool credentials and secrets system (Python API, Vue client) and guided its implementation across the team.
- Cut the main stylesheet by two thirds (3.7 MB to 1.2 MB) and documentation CI from about 83 to 15 minutes.
- Fixed production bugs, including a webhook regression that hit about 1,000 users.

As a core committer I review cross-team changes, mentor contributors and take part in technical hiring.

I use AI coding agents every day (Claude Code, Codex, Cursor) and build AI-enabled products in my own time. Decisions, review and quality stay mine.

## Selected work

### [Galaxy](https://github.com/galaxyproject/galaxy)

Open-source data analysis platform with 650,000+ registered users on its public services in Europe, the US and Australia. I contributed to the Galaxy client as a volunteer before joining the team in August 2022, and have been a core committer since August 2024.

- Scoped and designed Galaxy's command palette (Cmd/Ctrl+K) end to end: data layer and caching, UI, and extension points for reuse.
- Contributed to the [Galaxy Hub](https://github.com/galaxyproject/galaxy-hub) rewrite from Gridsome (Vue 2) to Astro (4,300+ pages migrated, URLs and SEO kept) and presented it at GCC2026.
- [RSEc Atlas](https://github.com/research-software-ecosystem/RSEc-Atlas): Nuxt and TypeScript catalogue for exploring metadata across 45,000+ research software tools, with search and filtering, shareable URLs and statically compiled metadata. Split the search index so the first results load after 1.2 MB instead of 5.4 MB.

### Apply Assistant

Job-application platform in private beta with selected users. It automates every step up to submission (research, tailoring, compile, form-answer drafts); the user reviews and submits. A remote MCP server lets agents work with per-scope tools and a review queue where the user approves each agent patch. Built with Next.js, React and TypeScript on Cloudflare Workers, D1 and R2.

### [Discens](https://github.com/itisAliRH/discens)

AI-powered language learning app that began as a 48-hour prototype. Built with Next.js, TypeScript and Supabase, with FSRS spaced repetition, AI-generated quizzes and voice conversation (OpenAI, ElevenLabs).

### [heidari.me](https://heidari.me)

English and German case-study site that agents can read (llms.txt, markdown negotiation, WebMCP), with Playwright and axe tests. Next.js static export on Cloudflare Pages.

## Tech stack

**Languages:** TypeScript, JavaScript, Python, SQL, Bash  
**Frontend:** Vue, Nuxt, React, Next.js, Pinia, Tailwind CSS, HTML, CSS  
**Backend and data:** Node.js, Express, FastAPI, REST APIs, GraphQL, PostgreSQL, Supabase, MongoDB  
**Testing and CI/CD:** Playwright, Cypress, Jest, Vitest, GitHub Actions  
**Cloud and DevOps:** Docker, Kubernetes, Vercel, Cloudflare, AWS, Linux  
**AI-assisted development:** GitHub Copilot/Codex, Claude Code, Cursor  
**Practices:** open-source collaboration, code review, modular architecture, secure system design, technical mentoring

## Talks and publications

I have presented and contributed to work around Galaxy workflows, notification systems, Vuex-to-Pinia migration, search improvements, credential handling, and FAIR research software.

A full list is available on [my website](https://heidari.me) and [ORCID](https://orcid.org/0000-0003-0315-4403).

## Links

- Website: https://heidari.me
- LinkedIn: https://www.linkedin.com/in/itisalirh/
- GitHub: https://github.com/itisAliRH
- Email: alireza@heidari.me
