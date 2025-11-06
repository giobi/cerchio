# Cerchio

Portale genitori Seconda Elementare - Anno Scolastico 2024/2025

## Features

- Password protection (statica: `cerchio2025`)
- Bacheca comunicazioni
- Info in evidenza (classe, rappresentante, eventi, contributi)
- Design friendly genitori-scuola
- Responsive mobile

## Stack

- GitHub Pages (statico)
- HTML + CSS + JavaScript vanilla
- Google Fonts (Quicksand + Open Sans)
- Earth Warm palette

## Setup

1. Clone repo
2. Edit `index.html` per aggiornare info classe/rappresentante
3. Push to GitHub
4. Configure DNS: `cerchio.giobi.com` CNAME → `giobi.github.io`

## Password

Password attuale: `cerchio2025`

Per cambiarla, modifica la riga in `index.html`:
```javascript
const correctPassword = 'cerchio2025';
```

## Aggiungere Post

Modifica la sezione `.posts-grid` in `index.html` e aggiungi card:
```html
<div class="post-card">
    <div class="post-date">GG Mese AAAA</div>
    <h3>Titolo Post</h3>
    <p>Contenuto...</p>
</div>
```

---

Created: 2025-11-06
Maintainer: Giobi
