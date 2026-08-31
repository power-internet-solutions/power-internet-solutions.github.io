# Customer Pages

Έτοιμο βασικό project για GitHub Pages + Jekyll με:
- ένα κοινό template για όλους τους πελάτες
- ξεχωριστό αρχείο δεδομένων ανά πελάτη
- responsive κάρτα
- vCard
- QR code vCard
- κουμπί λήψης `.vcf`

## ΠΡΟΣΟΧΗ

Το `assets/js/qrcode.min.js` πρέπει να είναι το πραγματικό browser build της βιβλιοθήκης QRCode.js.

Κατέβασε το `qrcode.min.js` από το επίσημο repository:
https://github.com/davidshimjs/qrcodejs

και βάλε το αρχείο στο:
`assets/js/qrcode.min.js`

## Προσθήκη πελάτη

Αντέγραψε π.χ. το `_customers/nikos.md` σε `_customers/petros.md` και άλλαξε τα στοιχεία και το `permalink`.

## GitHub Pages

Για repository `USERNAME.github.io`:
- https://USERNAME.github.io/giannis/
- https://USERNAME.github.io/nikos/
- https://USERNAME.github.io/ana/

Μην αποθηκεύεις ευαίσθητα προσωπικά δεδομένα σε public repository.
