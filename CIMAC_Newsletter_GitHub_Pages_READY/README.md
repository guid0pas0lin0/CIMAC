# CIMAC Newsletter Preview – GitHub Pages

Pacchetto pronto per essere pubblicato con GitHub Pages.

## Struttura

- `index.html` — indice cliente con link alle anteprime
- `newsletters/<slug>/index.html` — singola newsletter
- `newsletters/<slug>/assets/` — immagini della newsletter
- `.nojekyll` — evita elaborazioni Jekyll non necessarie

## Pubblicazione rapida

1. Crea un repository GitHub (es. `cimac-newsletter-preview`).
2. Carica **il contenuto di questa cartella** nella root del repository.
3. Vai in **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**.
5. Seleziona branch `main` e cartella `/ (root)`, quindi **Save**.
6. GitHub mostrerà l'URL pubblico della pagina.

Esempio: `https://NOME-UTENTE.github.io/cimac-newsletter-preview/`

## Nota

Questa cartella è una preview web. Il link di disiscrizione MailUp è volutamente disattivato nelle anteprime; i file MailUp originali non vengono modificati.
