# Demo Clinic App

A frontend-only, interactive UX/UI demo for a dental clinic management system — built with Tailwind CSS (via CDN) and vanilla JavaScript, no build step, no backend.

**Live demo:** enable GitHub Pages on this repo (Settings → Pages → Deploy from branch → `main` / root) and it'll be served directly from `index.html`.

## What's in here

Six modules, all in a single `index.html`, with realistic seed data and working interactions:

- **Patient Registration** — new patient intake, medical history questionnaire, returning-patient search
- **Dentist Portal** — a tap-based FDI odontogram (permanent + temporary teeth), quick-select prescriptions with allergy-conflict warnings, and a signature-based tooth-extraction consent flow
- **Inventory** — stock levels with low-stock alerts and multi-item stock in/out
- **Payments** — payment recording by mode (cash / GCash / bank transfer) and prescription printing
- **Attendance** — a simulated facial-recognition kiosk with a manual PIN fallback
- **Analytics** — visit trends, revenue, treatment/prescription breakdowns, inventory and attendance overviews

This is a design/UX prototype, not production software — data lives in memory and resets on reload. It's meant to demonstrate look, feel, and interaction flow ahead of a full Laravel build.

## Running it locally

Just open `index.html` in a browser — no server or build step required.
