# Diario allenamenti

Pagina statica (GitHub Pages) con una settimana per volta: scheda e valutazione post allenamento per ogni seduta.

## Pubblicare
1. Crea un repository (es. `allenamenti`) e carica tutti i file di questa cartella (`.nojekyll` incluso).
2. Settings → Pages → Source: branch `main`, cartella `/ (root)`.
3. Su iPhone apri `https://<utente>.github.io/allenamenti/` in Safari → Condividi → Aggiungi a Home.

## Come funziona
- `data/plan.json` contiene le schede (si aggiornano con un commit).
- Le valutazioni stanno nel browser del telefono (localStorage), non nel repository.
- Backup: Dati e sincronizzazione → Scarica file / Copia JSON, oppure sincronizza con un repository **privato** (token fine-grained, solo Contents: Read and write).
- "Copia riepilogo" mette in appunti la settimana in testo, da incollare nella chat con Claude.

## Attenzione
Il repository di una pagina GitHub Pages gratuita è pubblico: non metterci le valutazioni (dolori, sonno).
