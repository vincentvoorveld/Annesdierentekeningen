# Anne's Dieren Tekeningen Website

## Project Overview

**Purpose**: Portfolio website voor Anne's Dieren Tekeningen - een showcase voor handgemaakte dierentekeningen  
**Stack**: Statische HTML/CSS/JavaScript website  
**Status**: Volledig functioneel en klaar voor GitHub Pages deployment  
**Created**: November 8, 2025

## Project Structure

```
.
├── index.html              # Hoofdpagina met alle secties
├── style.css               # Styling met warme pastelkleuren
├── script.js               # Lightbox en smooth scrolling functionaliteit
├── images/                 # Galerie afbeeldingen en foto's
│   ├── anne-portret.jpg    # Portretfoto van Anne
│   ├── placeholder-1.jpg   # Hert tekening
│   ├── placeholder-2.jpg   # Golden Retriever tekening
│   ├── placeholder-3.jpg   # IJsvogel tekening
│   ├── placeholder-4.jpg   # Uil tekening
│   ├── placeholder-5.jpg   # Vos tekening
│   └── placeholder-6.jpg   # Zwarte kat tekening
├── README.md               # Project documentatie
└── replit.md               # Dit bestand
```

## Website Secties

1. **Header**
   - Titel en subtitel
   - Sticky navigatiebalk met smooth scrolling
   - Responsive menu

2. **Home**
   - Hero sectie met welkomstbericht
   - Gradient achtergrond in pastelkleuren

3. **Over Anne**
   - Portretfoto van Anne
   - Persoonlijke introductie
   - Informatie over technieken en materialen
   - Expositielocaties
   - Responsive layout: afbeelding naast tekst (desktop) of boven tekst (mobiel)

4. **Galerie**
   - 6 echte tekeningen van Anne (hert, hond, ijsvogel, uil, vos, zwarte kat)
   - Lightbox functionaliteit bij klikken
   - Keyboard navigatie (pijltjes, escape)
   - Responsive grid layout

5. **Bestellen**
   - Prijsinformatie (€50 voor A4 kleurpotlood)
   - Specificaties (formaat, materialen)
   - Extra informatie over maatwerk

6. **Contact**
   - Facebook link (nog in te vullen)
   - E-mail link (nog in te vullen)
   - Geen werkend formulier (zoals gevraagd)

7. **Footer**
   - Copyright notice
   - Social media iconen (Facebook, Instagram)

## Design Kenmerken

- **Kleurenschema**:
  - Primary: #f4e8e0 (beige)
  - Secondary: #ffd4d4 (lichtroze)
  - Accent: #c8e6c9 (pastelgroen)
  - Text: #4a4a4a (donkergrijs)

- **Typography**: Poppins (Google Fonts)
- **Stijl**: Zachte schaduwen, ronde hoeken, rustige uitstraling
- **Responsive**: Mobile-first design met media queries

## JavaScript Functionaliteiten

1. **Lightbox**
   - Klik op galerie afbeelding om te vergroten
   - Navigatie met prev/next knoppen
   - Keyboard navigatie (←, →, Escape)
   - Click buiten afbeelding om te sluiten

2. **Smooth Scrolling**
   - Vloeiende navigatie tussen secties
   - Compensatie voor sticky header hoogte

## Deployment naar GitHub Pages

De website is volledig statisch en direct deploybaar naar GitHub Pages:

1. Gebruik "Connect to GitHub" knop in Replit
2. Push code naar GitHub repository
3. Enable GitHub Pages in repository settings
4. Klaar!

## Nog aan te passen

- [ ] Facebook pagina URL invullen (meerdere locaties in index.html)
- [ ] E-mailadres vervangen in contact sectie
- [ ] Instagram link toevoegen (optioneel)
- [x] Echte tekeningen toegevoegd aan galerie (hert, hond, ijsvogel, uil, vos, zwarte kat)

## Development

De website draait op een Python HTTP server op poort 5000.

**Workflow**: `python -m http.server 5000`

## Recent Changes

- 2025-11-08: Initiële opzet van de volledige website
  - HTML structuur met alle gevraagde secties
  - CSS styling met warme pastelkleuren
  - JavaScript voor lightbox en smooth scrolling
  - Workflow configuratie voor lokale development
  - Echte tekeningen van Anne toegevoegd aan galerie (hert, golden retriever, ijsvogel, uil, vos, zwarte kat)
  - Portretfoto van Anne toegevoegd aan "Over Anne" sectie met responsive grid layout