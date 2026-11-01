# Inspect Lab

Palestra pratica per imparare i DevTools di Chrome su un e-commerce finto, **Maison Velluto**,
costruito come un'architettura reale: Akeneo → integrazione → Algolia (PLP) e SAP Commerce Cloud (PDP) → Adobe Analytics.

Online su **https://leonardonovelli.design/inspect-lab/**. Usalo con Chrome o Edge da computer.

## Struttura
- `index.html`: pagina d'ingresso
- `shop/`: il negozio (pagine, JS, CSS, risposte simulate di Algolia, SAP OCC e Adobe)
- `coach/coach.js`: il pannello delle lezioni (generato, non modificare a mano)
- `_src/`: sorgenti di dati, lezioni e coach. Non viene pubblicata.

## Modificare
Dopo aver cambiato qualcosa in `_src/` rigenera il sito:

```bash
node _src/build.mjs
```
