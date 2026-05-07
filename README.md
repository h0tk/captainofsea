# Captain of Sea - Full Stack Game Portal

Modern, secure and multilingual web platform for the **Captain of Sea** game ecosystem.

## Live Project

- Website: [https://captainofsea.com](https://captainofsea.com)

## What This Project Includes

- Full authentication flow (register/login/JWT/session tracking)
- Role-based admin panel (`owner`, `moderator`, `player`)
- Security hardening (rate limit, brute-force controls, owner protection)
- Advanced shop system with dynamic categories and coin packs
- Persistent floating cart with quantity controls
- Multi-currency price rendering by language with live exchange-rate conversion
- Support ticket system with threaded messages + image attachments
- Discord webhook notifications for support flow
- Announcement + ticker system
- Top-10 leaderboard with real database users
- Internationalization (multi-language UI support)

## Tech Stack

- **Frontend:** React, TypeScript, Vite, TailwindCSS
- **Backend:** Node.js, Express
- **Database:** SQLite
- **Infra/Deploy:** Caddy reverse proxy, Windows services (NSSM)
- **Integrations:** Discord webhook / bot workflows

## Highlights I Am Proud Of

- Built a secure role/permission model with strict owner protection.
- Designed a complete support-ticket workflow from UI to backend persistence.
- Implemented a dynamic shop editor in admin panel for non-technical management.
- Added language-aware currency display with real-time TRY conversion.
- Structured the project for real deployment and long-term maintenance.

## Security Notes

- Protected privileged account operations (role, ban, balance, deletion restrictions).
- Added endpoint-level rate limiting on sensitive actions.
- Hardened auth/session behavior and admin-only controls.

## Project Goal

Deliver a production-ready portal that combines:

- game community management,
- commerce-ready UX,
- admin automation,
- and secure account operations

in one unified platform.

---

If you want, I can also generate a second version focused on **recruiters** (short and business-oriented) and one focused on **developers** (more technical architecture details).
