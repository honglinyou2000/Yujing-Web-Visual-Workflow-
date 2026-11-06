# Yujing Web Visual Workflow (EN)

**Skill name:** High-Aesthetic Company Website Visual Workflow  
**When to use:** Building or restyling a company website / landing page that must look professional, tech-forward, strongly interactive, and not “AI-template.”

---

## What this skill does

It walks an agent through a **five-stage pipeline** so visual and frontend work stays intentional:

1. **Direction** — lock aesthetic POV (type, color, composition, one signature motion)  
2. **System** — freeze reusable design tokens and motion rules  
3. **Build** — implement sections with strong interaction, always skippable / reducible  
4. **De-slop** — remove generic AI look without killing the requested motion intensity  
5. **Polish** — screenshot-level audit (desktop + mobile) before handoff  

It does **not** invent company facts, credentials, case metrics, or unapproved product claims.

---

## Fixed inputs (align before running)

- Audience + one-line positioning (final slogan if already chosen)  
- IA rule: diagnose first, then propose — no thick product catalog pages  
- Brand: logo/palette if missing → temporary tokens marked “pending brand”  
- Motion default: Strong / Standard / Reduced (honor `prefers-reduced-motion`)  
- Reference texts in-repo: `design-skills/` (`frontend-design`, `ui-ux-pro-max`, `taste-skill`, `impeccable` + animate)

---

## Five stages (strict order; load one rule set at a time)

### 1. Direction (frontend-design)
- Write a **Direction Card**: mood keywords, type pairing, primary/accent color, grid system, **one signature move** (e.g. scroll “current” along the method axis, magnetic CTA)  
- Ban defaults: purple gradients + Inter everywhere + three icon cards  
- Mood anchors (editable): calm engineering / precision instrument / console lighting up — not party confetti  
- Output: `docs/DESIGN-direction.md` — get human sign-off before heavy UI

### 2. System (UI UX Pro Max)
- Tokens: color, type scale, spacing (4/8 grid), radius, elevation, component states  
- Motion: meaningful scroll narrative + micro-interactions; GSAP-style presets OK if performance holds  
- Output: `docs/DESIGN.md` or CSS variables — then build sections

### 3. Build (tokens → sections → states)
- Strong-interaction checklist (trim per page): scroll storytelling, section progress, magnetic buttons, card lift/sweep light, number easing, grid/glow parallax, short route transitions, method-page axis unlock  
- Guardrails: no forced long intros; CTA always clickable; copy never obscured by motion; offer Strong / Standard / Reduced (or at least system reduced-motion)  
- Product names only if approved for public use; unauthorized cases → honest empty states

### 4. De-slop (Taste rules; do not copy its quiet-motion ceiling)
- Keep: anti-template rules, one primary block per screen, even side edges, real-feeling visuals  
- Drop: empty decoration piles, low-contrast gray text, cards-in-cards, random purple headline gradients  
- If the brief asks for **strong** motion, follow the brief + stages 2–3; borrow Taste only for anti-slop

### 5. Polish (Impeccable, including animate)
- Batch issues from rendered desktop + mobile, then fix, then re-check  
- Check hierarchy, spacing, contrast, focus, touch targets, responsive, whether motion communicates  
- Kill meaningless looping animation

---

## Copy / business boundaries

- Visual quality only — no fabricated company story, licenses, or metrics  
- Credentials / cases / data: approved materials only; else mark pending or empty state  
- “Diagnose → then solution” IA beats thin product-brochure pages

---

## Done when

- Direction Card + tokens exist  
- At least one page (usually Home or How We Work) is interactively previewable  
- Strong and reduced-motion paths both usable  
- Audit list cleared or leftovers explicitly listed with reasons

---

## One-liner

> Turn a company site brief into a distinctive, tech-feel, high-interaction UI by running direction → tokens → build → de-slop → polish — without inventing business facts.
