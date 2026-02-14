# Pokemon Evolution Card Book

Interactive Pokemon TCG collection tracker — track all 9 generations with evolution chains, 90+ Trainer/Energy/Stadium cards, a live dashboard, and auto-saving progress.

## Features

- **1000+ Pokemon** across all 9 generations, grouped by evolution chains
- **90 Trainer, Energy & Stadium cards** with real TCG artwork (via TCGdex)
- **Live dashboard** — total cards, distinct found/total by stage, completed evolution sets
- **Auto-save** — your progress is saved in the browser automatically (localStorage)
- **Type & weakness info** loaded live from PokeAPI
- **Stage badges** (Basic, Stage 1, Stage 2, Baby, Legendary, Mythical)
- **Search & filter** across all card categories
- **Print mode** — prints a blank template with empty checkboxes & write-in counter boxes
- **Mobile-friendly** — works on phone, tablet & desktop

## Deployment

### GitHub Pages (free)

1. Create a new GitHub repository
2. Upload the `webapp/` folder contents (or push this folder as root)
3. Go to **Settings → Pages → Source** → select `main` branch, root folder
4. Your app will be live at `https://your-username.github.io/repo-name/`

### Netlify (free)

1. Go to [netlify.com](https://netlify.com) and sign in
2. Drag & drop the `webapp/` folder onto the deploy area
3. Done — you'll get a `https://something.netlify.app` URL

### Vercel (free)

1. Go to [vercel.com](https://vercel.com) and sign in
2. Import or drag & drop the `webapp/` folder
3. Done — you'll get a `https://something.vercel.app` URL

## After Deploying

1. Copy your live URL
2. Update `APP_URL` in `generate_access_card.py`
3. Re-run the script to generate the access card PDF with the correct QR code
4. Bundle the PDF for your Etsy listing

## Tech Stack

- Single HTML file (zero dependencies to install)
- [PokeAPI](https://pokeapi.co/) for sprites, types, and weaknesses
- [TCGdex](https://tcgdex.dev/) CDN for Trainer/Energy/Stadium card artwork
- Google Fonts (Fredoka + Press Start 2P)
- localStorage for persistence

## License

For personal and commercial use. Created as an Etsy digital product.
