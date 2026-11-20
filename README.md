# Risolute – sito web

Sito ufficiale di **Risolute**: consulenza antincendio e project management tecnico per imprese, attività del terziario e gestori di immobili.

🌐 **https://www.risolute.it**

## Struttura

| File | Contenuto |
|---|---|
| `index.html` | Home: servizi, metodo, percorsi, FAQ e modulo di contatto |
| `chi-siamo.html` | Chi siamo: Riccardo Ricotta, Founder e CEO |
| `privacy.html` | Informativa privacy e cookie (non indicizzata) |
| `404.html` | Pagina di errore per i link non validi |
| `firma-risolute.html` | Firma email da copiare nel programma di posta (non indicizzata) |
| `assets/img/` | Immagini ottimizzate in WebP, in più dimensioni |
| `assets/fonts/` | Caratteri DM Sans e Manrope ospitati in locale, con licenza OFL |
| `risolute-logo-light.svg`, `risolute-favicon.svg` | Logo e icona vettoriali |
| `favicon.ico`, `apple-touch-icon.png`, `site.webmanifest` | Icone per browser e smartphone |
| `og-image.png` | Anteprima per la condivisione su social e chat |
| `risolute-profilo.png` | Logo quadrato in alta risoluzione (immagine profilo) |
| `risolute-firma-v2.png` | Logo usato nella firma email |
| `sitemap.xml`, `robots.txt` | Indicizzazione sui motori di ricerca |
| `CNAME` | Dominio personalizzato per GitHub Pages |

## Scelte tecniche

- **Statico e senza dipendenze**: HTML e CSS scritti a mano, con poco JavaScript inline. Non serve nessuna build.
- **Nessuna richiesta a terzi durante la navigazione**: caratteri e immagini sono ospitati sul sito. Gli unici servizi esterni sono GitHub Pages (hosting) e Formspree (invio del modulo).
- **Prestazioni e accessibilità**: Lighthouse dà 100 in tutte le categorie (prestazioni, accessibilità, best practice e SEO) su mobile e desktop.
- **SEO**: dati strutturati schema.org (`ProfessionalService`, `WebSite`, `FAQPage`, `Person`, `BreadcrumbList`), meta Open Graph e sitemap.

## Come aggiornare

1. Modifica i file HTML direttamente, anche dall'editor di GitHub.
2. Se cambi i contenuti, aggiorna `<lastmod>` in `sitemap.xml`.
3. Per una nuova immagine, salvala in `assets/img/` in formato WebP. Prepara più larghezze (per esempio 640, 1040 e 1400 px) e usa `srcset`.
4. GitHub Pages pubblica il sito automaticamente dopo ogni modifica sul ramo `main`.

## Crediti

- Foto: [Unsplash](https://unsplash.com) (licenza Unsplash)
- Caratteri: [DM Sans](https://github.com/googlefonts/dm-fonts) e [Manrope](https://github.com/googlefonts/manrope), SIL Open Font License 1.1
