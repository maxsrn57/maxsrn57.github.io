# Sito personale — Massimo Saracino

Portfolio personale a 5 pagine in HTML, CSS, Sass e Bootstrap, con la sezione Progetti aggiornata al percorso completo di UX/UI Design (start2impact).

## File da caricare su GitHub

```
index.html
sudime.html
progetti.html
cv.html
contact.html
favicon.svg
Massimo Saracino.jpg
css/style.scss   (facoltativo, è il "codice sorgente" Sass)
css/style.css    (obbligatorio, è il CSS compilato usato dalle pagine)
assets/pdf/*.pdf (12 PDF dei progetti UX/UI, ~30 MB totali)
```

## Come pubblicare con GitHub Pages

1. Repository già pubblicato: `maxsrn57.github.io`, live su `https://maxsrn57.github.io/`.
2. Carica (sovrascrivendo) i file modificati: `index.html`, `sudime.html`, `cv.html`, `progetti.html`, `css/style.css`, `css/style.scss`.
3. Crea la cartella `assets/pdf` nel repository e carica dentro i 12 PDF presenti in `assets/pdf` di questa cartella locale (mantieni gli stessi nomi file, sono quelli linkati da `progetti.html`).

## Struttura del sito

- **Home** (`index.html`): presentazione breve, strumenti principali, link social.
- **Su di me** (`sudime.html`): il percorso da progettista tecnico CAD a UX/UI Designer in formazione.
- **Progetti** (`progetti.html`): 14 progetti in ordine cronologico — 12 case study del Corso UX/UI Design (Intro, Grafica, Copywriting, Discovery, Accessibilità, Wireframing, User Interface) più i 2 progetti del modulo HTML/CSS (landing page GreenEarth, questo sito).
- **CV** (`cv.html`): profilo, esperienza professionale, formazione, competenze.
- **Contattami** (`contact.html`): form di contatto, senza email/telefono esposti direttamente.

## Se modifichi lo stile (Sass)

```
npm install sass
npx sass css/style.scss css/style.css --style=expanded
```

## Requisiti del progetto soddisfatti

- 5 pagine (Home, Su di me, Progetti, CV, Contattami), con CV in HTML.
- Pagina "Contattami" con form, senza email/telefono esposti direttamente.
- Framework front end: Bootstrap 5.
- Preprocessore CSS: Sass (`style.scss` → `style.css`).
- Favicon (SVG con iniziali).
- Menu di navigazione sticky, anche su mobile.
- Layout con CSS Grid (competenze, progetti) e Flexbox (hero, social, strumenti, form).
- Sito responsive (media query per mobile).
- Tag Open Graph su tutte le pagine.
- Pagina progetti con 14 case study reali, collegati a PDF, repository GitHub e siti live.
