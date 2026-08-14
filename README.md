<p align="center">
  <img src="u/icons/icon-192.png" width="72" alt="Treino">
</p>

<h1 align="center">Treino</h1>

<p align="center">
  <em>A language trainer that speaks your language — and your partner's.</em><br>
  <a href="https://t.seedwave.pt/u/?pair=ru-en&lang=ru">Live demo</a> ·
  <a href="https://seedwave.pt/hub/">SeedWave Hub</a> ·
  <a href="https://www.linkedin.com/in/igor-kartuzov">Built by Igor Kartuzov</a>
</p>

---

## The problem
Generic language apps treat every learner the same. Real practice is personal — it depends on the pair of languages you're crossing and the person doing the crossing. A one-size deck is the wrong tool.

## The build
Treino is a multilingual trainer built on the SeedWave **three-layer architecture** — `engine / locales / content`. The root is a redirect into `/u/` that preserves `?pair=`, `?d=`, `?lang=` and `#hash`, so a link opens straight into a personal deck. A new learner is a new deck; a new language is a new dictionary — never a rebuild.

## Stack
`SeedWave three-layer engine` · `URL-param personal decks` · `GitHub Pages` · `multilingual (RU/EN/PT/ES/DE)`

## See it live
- **Demo:** https://t.seedwave.pt/u/?pair=ru-en&lang=ru
- **Personal deck:** `/u/?pair=ru-en&d=olga&lang=ru` — one link, one learner.

## Screenshots
<!-- TODO: add 1–3 clean screenshots of a personal deck. Show the product, not the code.
<p align="center">
  <img src="screenshot-1.png" width="320" alt="Treino — personal deck">
</p>
-->

## What's reusable
- **Three-layer engine** — `engine / locales / content`. Add a language = add a dictionary file. The engine never changes.
- **Personal deck via URL** — identity and language live in the link (`?pair=&d=&lang=`), so distribution is a single URL.

## Status & next
- **Status:** flagship multilingual MVP — live.
- **Next:** English / Portuguese decks; unify the top bar to the series standard (language + theme buttons).

---

<p align="center">
  <sub>© Igor Kartuzov · <a href="https://seedwave.pt/hub/">SeedWave</a> — AI-first studio · Madeira, EU</sub>
</p>
