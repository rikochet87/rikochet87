<div align="center">

# Matías Rosello

### AI-assisted software developer · GIS & geospatial systems

I build complete, working systems for real problems — from the field to production — with AI as a core part of how I design and write code.

📍 Resistencia, Chaco, Argentina · 📧 rosellomatias87@gmail.com

</div>

---

## About me

In 2022 I took over the GIS area of the road maintenance department of Chaco Province, Argentina. There was no digital data. Today the **~29,000 km rural road network and its 103 maintenance consortiums** run on a system I designed and built: an offline-first Android app for field technicians and a web platform for the office, with maps, surveys, budgets and hydrology.

I also build products of my own and for clients: a conversational AI assistant in production on the Anthropic API, a 2D CAD application written from scratch, management systems for small businesses and mobile apps.

I work end to end: I understand the problem, design the solution, build it with AI agents (Claude Code) and put it in the hands of the people who use it.

**Background that shapes how I work:**

- 🏗️ Civil Engineering studies at UNNE (4 years)
- 📐 Years of CAD drafting and 3D modeling for architecture and engineering projects
- 🛰️ University Expert in Satellite Technology, Remote Sensing and GIS — UTN Buenos Aires (2024, 90 h)
- 🗺️ QGIS Integral: Spatial Data Analysis powered by ChatGPT — Centro REDES, CONICET associated unit (2024, 96 h, grade 10/10)
- 🛣️ Road Maintenance and Conservation — Faculty of Engineering, UNNE (2024)
- 📏 Training in AutoCAD and AutoCAD Civil 3D
- 🧠 Certified Ontological Coach (AACOP), with a focus on neurocoaching

---

## Featured work

### 🛰️ SIG Vial Chaco — road network management platform
*In daily use · [Showcase with screenshots](https://github.com/rikochet87/sig-vial-chaco-showcase) · [Live demo](https://sig-vial-chaco-panel.vercel.app/hidrologia/publico-85afwsdcuj)*

GIS platform for the provincial rural road network: 103 consortiums, 5 zones, ~29,000 km.

- **Android field app** (React Native + Expo): works with no signal and syncs when it reconnects, background GPS tracking, bridge and culvert inspection forms, photos.
- **Web platform** (Next.js + Supabase): interactive map, surveys, public works calculators and budgets, road equipment inventory, role-based permissions.
- **Hydrology module**: rainfall from ~70 rain gauges interpolated over the road network (IDW, Thiessen), Paraná river levels and forecasts, flood mapping for Greater Resistencia from satellite imagery, and a flood forecast for Barranqueras built from rainfall in Brazil.
- **Public reporting tools**: anyone can report road conditions or roadkill wildlife from their phone, with no account.

`TypeScript` `React Native` `Next.js` `Supabase / PostgreSQL` `Leaflet` `QGIS` `Google Earth Engine`

### 🤖 Aión — AI companion for coaching processes
*In production, closed beta · [Showcase: what it is and how it works](https://github.com/rikochet87/aion-showcase)*

Conversational assistant that supports people between coaching sessions, based on the Ontology of Language. It complements a human coach; it doesn't replace one.

- Built on the **Anthropic API**, deployed on **Cloudflare Workers**.
- Process memory, user accounts, scheduled follow-ups and an admin panel.
- Installable web chat; WhatsApp integration in progress.

### 📐 TrazoCAD — 2D CAD in the browser
*Personal product · in development · [Showcase with screenshots](https://github.com/rikochet87/trazocad-showcase)*

AutoCAD-style technical drawing software written from scratch as an installable, offline PWA. Pure JavaScript, **zero dependencies, no build step**.

- AutoCAD command line and command names, with Spanish aliases.
- Reads and writes DXF (2007, 2000, R12), including 3D polylines, 3D faces and TIN surfaces.
- Handles real survey coordinates (Gauss-Krüger) with a local origin, so precision holds at any zoom.
- Automated tests in headless Chrome.

### 🧱 CalcuObra — construction calculators
*[Repository](https://github.com/rikochet87/arq-web-app)*

Draw a floor plan and get a bill of materials instantly. Upload an AutoCAD DXF and see it in 3D. Calculators for bricks, concrete, paint, ceramics, stairs and subfloors.

`JavaScript` `Three.js` `Vercel`

---

## Client work

| Project | What it is | Stack |
|---|---|---|
| **Football pitch management** | Bookings, POS with barcode scanner, stock and daily cash register for a 5-a-side pitch. Installable PWA. | React · Vite · Supabase |
| **[Trópico café](https://rikochet87.github.io/tropico-cafe/)** | Single-page website with a scroll-driven 3D walkthrough of the venue. | Three.js |
| **Método Pons** | Strength training app based on the method of Argentina's 5-time Strongest Man. | React Native · Firebase |
| **[Noe Ferreyra](https://noeferreyra.pages.dev)** | Landing page with self-hosted fonts and security headers. | HTML · CSS · Cloudflare Pages |

---

## How I work

```text
Understand the real problem  →  design the solution  →  build it with AI agents
        →  test it against real data  →  deliver it  →  learn and improve
```

- **AI is my main development tool, not a shortcut.** I write project guides (`CLAUDE.md`) that capture decisions, known pitfalls and how each part is verified, so every session builds on the last one.
- **I verify before I trust.** My projects include automated checks that compare results against known cases, official figures or independent sources.
- **I document what I measured and what I ruled out**, so nobody repeats the same mistake twice.

---

## Tech stack

| | |
|---|---|
| **Languages** | TypeScript · JavaScript · Python · SQL |
| **Frontend & mobile** | React · Next.js · React Native / Expo · Vite · PWA |
| **Backend & data** | Supabase / PostgreSQL · Firebase · Cloudflare Workers · Vercel |
| **GIS & maps** | QGIS · Leaflet · GeoJSON · Google Earth Engine · remote sensing |
| **AI** | Claude Code · Anthropic API · prompt engineering · AI agents |
| **Design & CAD** | AutoCAD · AutoCAD Civil 3D · Revit · SketchUp · Three.js |

---

## Languages

Spanish (native) · English (improving every day)

<div align="center">

**Open to remote work.** Let's talk: rosellomatias87@gmail.com

</div>
