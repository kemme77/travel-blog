# Kemme's Portfolio

Portfolio-Website, umgesetzt mit Next.js (App Router), Tailwind CSS und Prisma. Diese Repository-Version ist als Starter für eine persönliche Portfolio-Webseite gedacht.

## Übersicht
- Framework: Next.js (App Router)
- Styling: Tailwind CSS
- DB / ORM: Prisma
- Sprache: TypeScript
- Ziel: Vorstellung von Projekten, Skills und Kontaktdaten als statisch/dynamische Webseite

## Features (kurz)
- Startseite mit Projektübersicht: src/app/page.tsx
- Zentrale Layout-Komponente: src/app/layout.tsx
- Wiederverwendbare UI-Komponenten: src/components/ui (z. B. Button)
- Utility-Funktionen: src/lib/utils.ts
- Prisma-Schema: prisma/schema.prisma

## Projektstruktur (ausgewählte Pfade)
- src/app — Next.js App-Router Seiten & Layout
- src/components — UI- und Layout-Komponenten
- src/lib — Hilfsfunktionen
- prisma — Prisma-Schema
- public — statische Dateien

## Lokale Entwicklung
Voraussetzungen: Node.js (>=16), pnpm/npm/yarn, ggf. Docker (optional)

Beispielbefehle (Linux):
- Abhängigkeiten installieren:
  - npm install
- Development-Server starten:
  - npm run dev
- Produktion bauen:
  - npm run build
  - npm run start

## Prisma
- .env: Datenbankverbindung (DATABASE_URL) konfigurieren
- Prisma Client generieren / Migrationen:
  - npx prisma generate
  - npx prisma migrate dev --name init

## Deployment
- Eignet sich für Vercel oder Docker Compose (docker-compose.yml liegt im Projekt).
- Vor Deployment sicherstellen, dass ENV-Variablen (z. B. DATABASE_URL) gesetzt sind.

## Hinweise für die Webseite
- App Router (src/app) verwendet server- und client-components je nach Bedarf.
- Komponenten befinden sich in src/components — wiederverwendbare UI-Elemente zentral ablegen.

## Kontakt & Lizenz
Coming soon...

Dieses Projekt ist als persönliches Portfolio gedacht.
