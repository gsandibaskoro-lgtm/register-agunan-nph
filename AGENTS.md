# Agent instructions: Monitoring Agunan Kredit Bermasalah

For every UI change, read `.agents/skills/taste-skill/SKILL.md` first and apply its contextual anti-slop design guidance. Source: https://github.com/Leonxlnx/taste-skill (upstream skill copied into this repository).

This is an existing banking operations dashboard, not a marketing landing page. Preserve existing business logic, records, authentication, permissions, storage, realtime synchronization, exports, and PWA behavior. Audit existing UI and brand assets before changing them. Prioritize readable data tables, responsive mobile controls, accessible contrast, restrained motion, consistent status colors and typography. Never replace existing branding with a generic aesthetic. Do not introduce React/Next.js/Tailwind merely because the upstream skill mentions them; retain this project's existing HTML/CSS/JS stack. Test light/dark mode and mobile before shipping. Do not alter other repositories or Vercel projects.
