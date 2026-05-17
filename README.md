# Clarity — AI Reflection & Journaling Platform

Clarity is a partially built AI‑assisted journaling and reflection platform built with **React + Vite + Supabase + Stripe**.  
It helps users reflect on their thoughts through guided questions, snapshots, and pattern analysis.  
This repository contains the full source code for Clarity v1, including both client and server logic.

---

## Overview

Clarity includes:
- **Questioning Engine** — Generates guided reflection questions and follow‑ups.
- **Snapshot Engine** — Creates AI‑written summaries of user reflections.
- **Pattern Engine (server)** — Detects linguistic, emotional, and behavioral patterns over time.
- **Analytical Engine (client)** — Ten‑layer heuristic system that surfaces patterns, identity themes, and insights.
- **Two‑Person Mode** — Shared reflection sessions with simple heuristic insights.
- **Continuation Engine** — Tracks habits and ongoing reflection continuity.
- **Identity Engine** — Builds evolving identity profiles based on reflection data.
- **Safety Subsystem** — Keyword‑based risk detection and local resource suggestions.
- **Clarity+ Premium** — Stripe‑powered subscription flow (sandbox mode).
- **Calm Visual Layer** — Ambient background and premium visual themes.

---

## Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React 18.3, Vite 5, TypeScript, Tailwind CSS |
| Backend | Supabase (Postgres, Auth, Storage, Edge Functions) |
| Payments | Stripe (sandbox keys configured) |
| AI Gateway | Lovable AI Gateway (LOVABLE_API_KEY) |
| Testing | Vitest + Testing Library (limited coverage) |

---

## Current Status

Clarity **runs**, but it is **unfinished**.  
Many modules are functional but heuristic or placeholder versions.  
The project is best suited for a developer or founder who wants a substantial head start on building an AI journaling or mental wellness product.

**Working components:**
- Supabase Auth (email + Google)
- Question/Answer recording
- Snapshot generation and sharing
- Pattern Engine pipeline
- Analytical Engine (v1 heuristic)
- Stripe sandbox checkout
- Two‑Person sessions
- Safety scanning

**Partially implemented:**
- Analytical Engine layers (v1 scaffolding)
- Premium Insights page (placeholder fallbacks)
- Continuation engine (UX integration incomplete)
- Two‑Person real‑time sync
- Identity timeline and pattern conversations

---

## Limitations & Disclaimers

This project is sold **strictly as‑is**.  
It is **unfinished** and may contain bugs, placeholder logic, incomplete flows, or non‑functional sections.  
Analytical outputs are **heuristic v1 versions** and should **not** be marketed as clinical or production‑grade.  
Stripe is configured in **sandbox mode only**.  
No warranties, guarantees, or ongoing support are provided.  
The safety subsystem is **not a clinical tool** and should not be used for mental‑health diagnosis or treatment.

By using or purchasing this codebase, you acknowledge that:
- You are responsible for your own implementation and deployment.
- The seller provides no liability for outcomes, data, or user behavior.
- The project is for educational and developmental use only.

---

## What’s Included

- Full Clarity v1 codebase
- Supabase schema (33 tables)
- 25+ edge functions (pattern, snapshot, continuation, identity, Stripe, safety)
- 10‑layer Analytical Engine
- UI components and pages (Daily Insights, Patterns, Story, Timeline, Premium)
- Stripe sandbox integration
- Documentation and audit files (AUDIT_PHASE_4.md, phase2‑cleanup‑checklist.md)

---

## License

This repository is provided **without warranty or guarantee**.  
Use, modification, and resale are permitted under the terms of the IndieMaker sale agreement.  
All branding (“Clarity”, “Clarity+”) may be renamed by the buyer after purchase.

---

## Author Notes

Clarity represents a large, multi‑engine AI journaling system in progress.  
It is not a finished SaaS product but a substantial foundation for future development.

---

## Legal Safety Summary

- Sold **as‑is**, **no refunds**, **no guarantees**.  
- Buyer assumes full responsibility for deployment and compliance.  
- Seller makes no claims of production readiness, clinical accuracy, or commercial viability.  
- This README and audit serve as factual documentation of the project’s current state.

---

