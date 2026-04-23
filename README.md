# BON APP! 🍽

Din personliga receptapp — byggd med React + Vite, installerbar som PWA.

## Deploya på Netlify (gratis, ~3 minuter)

### Alternativ A: Drag & drop (enklast)

1. Kör lokalt först för att bygga:
   ```
   npm install
   npm run build
   ```
2. Gå till [netlify.com](https://netlify.com) och skapa ett gratis konto
3. Dra och släpp mappen `dist/` till Netlify-dashboarden
4. Du får en URL direkt — t.ex. `https://bonapp-abc123.netlify.app`

### Alternativ B: GitHub (automatiska uppdateringar)

1. Skapa ett konto på [github.com](https://github.com) om du inte har ett
2. Skapa ett nytt repository och ladda upp alla filer
3. Gå till [netlify.com](https://netlify.com) → "Add new site" → "Import from Git"
4. Välj ditt repo — Netlify hittar `netlify.toml` automatiskt
5. Klicka "Deploy" — klart!

## Installera som app på iPhone

1. Öppna din Netlify-URL i **Safari** (måste vara Safari, inte Chrome)
2. Tryck på dela-ikonen (fyrkant med pil upp) längst ner
3. Välj **"Lägg till på hemskärmen"**
4. Tryck **"Lägg till"**

Nu har du BON APP! som en ikon på hemskärmen — precis som en riktig app!

## Installera som app på Android

1. Öppna din URL i Chrome
2. Chrome visar automatiskt en banner "Installera BON APP!"
3. Alternativt: tryck på menyn (⋮) → "Lägg till på startskärmen"

## Köra lokalt

```bash
npm install
npm run dev
```

Öppna [http://localhost:5173](http://localhost:5173)

## OBS: API-nyckel

Appen använder Anthropic API för AI-funktioner (bildmatchning, tips, inköpslistor).
Den är konfigurerad att köra utan nyckel i Claude.ai-miljön.

Om du kör appen fristående behöver du lägga till din API-nyckel.
Kontakta Anthropic på [anthropic.com](https://anthropic.com) för att skaffa en.
