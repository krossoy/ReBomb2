# Random Winner App

En nettbasert applikasjon for å trekke tilfeldige vinnere fra lister av deltakere, utviklet for Apex Sport & Trading Cards.

## 🎯 Funksjonalitet

### Kjernefunksjoner
- **Listeopprettelse**: Opprett nye lister med unike navn
- **Listeadministrasjon**: Legg til og slett deltakere fra lister
- **Tilfeldig vinner**: Trekk en tilfeldig vinner med 2-sekunders spinning-animasjon
- **Datapersistens**: Alle lister lagres automatisk i nettleserens localStorage
- **Merkeidentitet**: Inkluderer Apex Sport & Trading Cards-logo

### Design-elementer
- **Casino-inspirert design** med glødende effekter og animasjoner
- **Responsiv design** som fungerer på mobil, nettbrett og desktop
- **Fargepalett**: Svart bakgrunn (#000000), grønn aksent (#39FF14), gull for vinnere (#D4AF37)
- **Typografi**: Montserrat font for moderne utseende

## 🚀 Bruk

### Starte applikasjonen
1. Åpne `index.html` i en moderne nettleser
2. Eller kjør en lokal webserver: `python3 -m http.server 8000`
3. Gå til `http://localhost:8000` i nettleseren

### Brukerveiledning

#### 1. Lag en ny liste
- Skriv inn et navn for listen i "Lag Ny Liste"-feltet
- Klikk "Lag Liste"-knappen
- Listen blir automatisk valgt

#### 2. Legg til deltakere
- Velg ønsket liste fra nedtrekksmenyen
- Skriv inn navn på deltaker i "Legg til Deltaker"-feltet
- Klikk "Legg til" eller trykk Enter
- Deltakeren vises i listen nedenfor

#### 3. Administrer deltakere
- Se alle deltakere i den valgte listen
- Klikk "Slett" for å fjerne en deltaker
- Antall deltakere vises ved siden av listenavnet

#### 4. Trekk en vinner
- Sørg for at listen har minst én deltaker
- Klikk "🎲 Trekk Vinner!"-knappen
- Vent på 2-sekunders spinning-animasjon
- Vinneren annonseres med gull-gradient og pulserende effekt

## 🛠 Tekniske detaljer

### Teknologier
- **React.js 18** for dynamisk brukergrensesnitt
- **Tailwind CSS** for styling og responsivt design
- **Vanilla JavaScript** for logikk og localStorage-håndtering
- **Montserrat font** for typografi
- **CSS animasjoner** for casino-effekter

### Nettleser-kompatibilitet
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Ytelse
- Rask lasting (< 3 sekunder)
- Minimal minneforbruk
- Ingen eksterne API-kall

## 📱 Responsivt design

Appen er optimalisert for:
- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: 1024px+

## 💾 Datalagring

- Alle lister lagres lokalt i nettleserens localStorage
- Ingen data sendes til eksterne servere
- Data bevares mellom økter
- Maksimal lagringskapasitet: ~5-10 MB

## 🎨 Designspesifikasjoner

### Farger
- **Bakgrunn**: Svart (#000000) med gradient
- **Primær aksent**: Grønn (#39FF14) fra Apex-logo
- **Sekundær aksent**: Gull (#D4AF37) for vinnere
- **Tekst**: Hvit (#FFFFFF) for lesbarhet

### Animasjoner
- **Spinning**: 2-sekunders rotasjon ved vinnertrekning
- **Winner pulse**: Pulserende gull-effekt for vinnertekst
- **Hover-effekter**: Glødende knapper og scale-transformasjoner
- **Card flip**: Subtil animasjon ved visning av deltakere

## 🔧 Tilpasning

### Logo
For å bytte logo, erstatt `apexLogo` base64-strengen i koden med din egen logo.

### Farger
Rediger CSS-variablene i `<style>`-seksjonen for å tilpasse fargeskjemaet.

### Animasjoner
Juster varighet og effekter i CSS `@keyframes`-reglene.

## 📄 Lisens

© 2024 Apex Sport & Trading Cards

---

*Utviklet i henhold til Product Requirements Document (PRD) for Random Winner App*