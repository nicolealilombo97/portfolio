# Guida: dal sito alla pubblicazione

## 1. Personalizza i contenuti
- Cerca `nicolealilombo97` nei 3 file HTML e sostituiscilo con il tuo username GitHub.
- Nella cartella `img/` aggiungi solo `og-cover.jpg` (1200x630 px, per l'anteprima social): la tua foto e le copertine dei 4 progetti ci sono già. I PDF dei case study sono nella cartella `pdf/`.
- In `cv.html` completa laurea, master, lingue e aggiungi 1-2 risultati concreti sotto l'esperienza.
- Nei link LinkedIn, GitHub e Figma inserisci i tuoi indirizzi reali.

## 2. Attiva il form (Formspree, gratuito)
1. Registrati su formspree.io e crea un nuovo form.
2. Copia il suo URL (tipo `https://formspree.io/f/abcd1234`).
3. In `contatti.html` sostituisci `INSERISCI_IL_TUO_ID` nell'attributo `action`.

## 3. Modificare gli stili (Sass)
Gli stili si scrivono in `scss/style.scss`. Dopo ogni modifica compila:
```
npm install -g sass
sass scss/style.scss css/style.css
```
Cambia poi `?v=1.0` in `?v=1.1` nei link al CSS per aggiornare la cache.

## 4. Pubblica su GitHub Pages
1. Su github.com crea un repository pubblico chiamato `portfolio`.
2. Carica tutti i file (pulsante "Add file" > "Upload files"), mantenendo le cartelle.
3. Vai in Settings > Pages, scegli "Deploy from a branch", branch `main`, cartella `/ (root)` e salva.
4. Dopo 1-2 minuti il sito sarà su `https://nicolealilombo97.github.io/portfolio/`.

## 5. Presentazione PDF (Canva)
Slide consigliate: 1) titolo e link, 2) obiettivo e pubblico, 3) scelte di design (colori, font), 4) struttura delle pagine, 5) tecnologie (HTML, CSS, Bootstrap, Sass, Flexbox, Grid), 6) responsive e menu sticky, 7) link a GitHub e al sito.
