# Hotel PAM — nový web

Moderní jednostránkový web horského střediska **Hotel PAM** (Jáchymov / Krušné hory), inspirovaný šablonou [The Hotel](https://thehotel.framer.website/).

## Spuštění

Stačí otevřít `index.html` v prohlížeči, nebo z této složky:

```bash
# Python
python -m http.server 5173

# nebo npx
npx --yes serve .
```

Pak otevřete http://localhost:5173

## Obsah

Data a texty pocházejí z [hotel-pam.cz](https://hotel-pam.cz/) (ubytování, ceny, služby, kontakt, příběh rodiny Jedličkových). Fotografie jsou především z oficiálního webu PAM; doplňkové atmosférické snímky z Unsplash. Recenze hostů z Booking.com a Travelking.

## Struktura

- `index.html` — stránka
- `styles.css` — styly (layout podle The Hotel)
- `main.js` — navigace a scroll animace
- `assets/images/` — fotografie
