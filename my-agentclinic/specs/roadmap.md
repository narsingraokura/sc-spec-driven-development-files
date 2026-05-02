# Roadmap

Each phase is a small, shippable increment. Complete one before starting the next.

## Phase 1 — Project scaffold
- Initialize Next.js 14 app with TypeScript and Tailwind CSS
- Set up Prisma with SQLite and run first migration
- Confirm `npm run dev` shows a working homepage

## Phase 2 — Data models
- Define Prisma schema: `Agent`, `Ailment`, `Therapy`, `Appointment`
- Seed the database with sample data
- Verify models via Prisma Studio

## Phase 3 — Agent listing
- `/agents` page: list all agents with name and current status
- Basic card layout styled with Tailwind

## Phase 4 — Agent detail
- `/agents/[id]` page: show agent profile, active ailments, assigned therapies

## Phase 5 — Ailments & therapies
- `/ailments` page: browse available ailment types
- `/therapies` page: browse available therapy types

## Phase 6 — Appointment booking
- Form to book an appointment (agent + therapy + date/time)
- Persist to database via API route
- Confirmation screen

## Phase 7 — Staff dashboard
- `/dashboard` page: list upcoming appointments, filter by agent or therapy
- Mark appointments complete or cancelled

## Phase 8 — UI polish
- Consistent navigation, responsive layout, loading states, empty states
- Accessibility pass (keyboard nav, ARIA labels)

## Phase 9 — Production readiness
- Swap SQLite for PostgreSQL
- Environment variable configuration
- Basic error handling and 404 pages
