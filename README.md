
# EU Capital — GitHub Pages pack (SK)

**Obsah:** `index.html`, `styles.css`, složka `assets/`, `sitemap.xml`, `robots.txt`  
**Připraveno pro GitHub Pages** — stačí nahrát do repozitáře a zapnout Pages (branch `main`, folder `/ (root)`).

## Postup nasazení
1. Vytvoř repo `eucapital-web` (Public).
2. Uploaduj všechny soubory z tohoto ZIPu do kořene repa.
3. Settings → Pages → Source: *Deploy from a branch*, Branch: `main` / `/ (root)`.
4. Otevři vygenerovanou URL (např. `https://tvoje-jmeno.github.io/eucapital-web/`).

## Výměna fotek
V `assets/` přepiš tyto soubory svými exporty z Canvy (ponech stejné názvy):
- `hero-office.jpg`
- `about-meeting.jpg`
- `portfolio.jpg`
- `testimonial.jpg`

## Logo
Nahraj `assets/logo-eu-capital.png` (PNG s průhledným pozadím). Velikost lze měnit v `styles.css`:
```css
:root{ --logo-header: 70px; --logo-hero: 148px; }
```

## Sociální sítě
Ve footeru nahraď `href="#"` reálnými URL (LinkedIn, Facebook, X/Twitter).

## Formulář
V `index.html` nahraď `https://formspree.io/f/XXXXXXXX` svým Formspree endpointem.
