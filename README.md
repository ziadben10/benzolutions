# BenZolutions — Portfolio (Next.js One‑Pager)

Strakke, foutloze one‑pager met NL/EN switch, demo‑chatbot en contactsectie.
Gebouwd met Next.js (App Router) + Tailwind. Eén root (`app/layout.tsx`), één pagina (`app/page.tsx`).

## Snel starten

```bash
npm i
npm run dev
# open http://localhost:3000
```

## Bouwen & draaien
```bash
npm run build
npm start
```

## Deploy (Vercel)
1. Push naar GitHub
2. Importeer repo in Vercel
3. **Root directory = project root** (waar `package.json` staat)
4. Framework preset: **Next.js**
5. Deploy

## Aanpassen
- Vervang WhatsApp in `app/page.tsx` bij `href="https://wa.me/31600000000...`
- Vervang e‑mail `contact@benzolutions.nl`
- Vervang logo in `public/logo.svg`
- Pas teksten aan in de `dict` in `app/page.tsx` (NL/EN)

## Chatbot Demo
De floating knop rechtsonder opent een simpele demo-chat. Vervang dit later met een echte embed (bijv. Chatbase of Zoho SalesIQ).

Succes! – BenZolutions
