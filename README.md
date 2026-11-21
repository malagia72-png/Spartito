# Spartito per pianoforte

App web installabile (PWA) per scrivere spartiti per pianoforte: doppio pentagramma, tempo in battuta, armatura, note puntate, terzine, accordi, travi, legature, segni di ripetizione, commenti e dinamiche. Salva e riapre gli spartiti (`.json`) ed esporta in PDF. Funziona anche offline.

## Pubblicarla con GitHub Pages (gratis)

1. Su github.com crea un account, poi **New repository**: nome `spartito`, **Public**, **Create repository**.
2. Nella pagina del repository tocca **uploading an existing file** e carica questi file (estraili prima dallo zip):
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`.
   Poi **Commit changes**.
3. Vai in **Settings → Pages**. Sotto *Build and deployment* scegli **Deploy from a branch**, ramo **main**, cartella **/ (root)**, poi **Save**.
4. Dopo uno o due minuti l'app è online all'indirizzo `https://TUO-NOME-UTENTE.github.io/spartito/`.

## Installarla sul telefono

- **iPhone (Safari):** apri l'indirizzo, tocca Condividi, poi **Aggiungi a Home**.
- **Android (Chrome):** apri l'indirizzo, menu ⋮, poi **Installa app**.

Apri l'app una prima volta con la connessione attiva: così si salva anche la libreria usata per il PDF e poi funziona offline.

## Aggiornare l'app

Carica di nuovo i file modificati (**Add file → Upload files**, stessi nomi, poi Commit). In `sw.js` cambia il numero di versione della cache (`spartito-v6` → `spartito-v7`), altrimenti i telefoni continuano a usare la copia vecchia. Poi riapri l'app una volta con la connessione.

## Salvare il lavoro

Il PDF serve per stampare. Per riprendere uno spartito usa **Salva file** (`.json`) e riaprilo con **Apri file**.
