# Arrivederci Lido

Checklist interattiva per chiudere le utenze del lido a fine weekend
(Appartamento 1 e Appartamento 2), con foto di ogni valvola/interruttore.
PWA installabile sull’iPhone, funziona anche offline.

## Pubblicazione su GitHub Pages

Metti questi file in una cartella del tuo repo delle Pages, ad esempio `lido/`:

```
lido/
  index.html
  manifest.webmanifest
  sw.js
  icon-192.png
  icon-512.png
  icon-180.png
```

Fai commit e push. Il link da condividere su WhatsApp sara’:

```
https://fedesynthesis.github.io/lido/
```

## Installazione sull’iPhone (per chi riceve il link)

Apri il link in Safari -> Condividi -> “Aggiungi a Home”. Comparira’
l’icona “casetta che dorme” come una vera app.

## Note

- Le spunte si salvano nel browser di chi usa la pagina (localStorage).
- Le foto sono incorporate nella pagina: nessun file esterno, niente da caricare a parte.
- I font Google si caricano da internet; offline si usa il font di sistema.