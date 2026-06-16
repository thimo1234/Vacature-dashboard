# Vacature Dashboard – Elevation Partners

Jouw persoonlijke vacature dashboard voor IT infrastructuur rollen in de regio Amsterdam.

## Wat doet het?

- Haalt automatisch vacatures op uit Indeed, Nationale Vacaturebank en ITjobs.nl
- Filtert freelance/ZZP vacatures eruit (alleen vast dienstverband)
- Filtert op bedrijfsgrootte: MKB / Mid-market / Enterprise
- Filtert op regio Amsterdam (jouw postcodes 1011–1069)
- Filtert op functiecategorie en salaris

---

## Online zetten in 5 minuten (gratis via Vercel)

### Stap 1 – Maak een gratis GitHub account
Ga naar https://github.com en maak een account aan als je die nog niet hebt.

### Stap 2 – Maak een nieuw repository aan
1. Klik op de groene knop "New" (linksboven)
2. Geef het een naam, bijvoorbeeld: `vacature-dashboard`
3. Zet hem op "Public"
4. Klik "Create repository"

### Stap 3 – Upload het bestand
1. Klik op "uploading an existing file"
2. Sleep het bestand `index.html` naar de uploadpagina
3. Klik "Commit changes"

### Stap 4 – Verbind met Vercel
1. Ga naar https://vercel.com en log in met je GitHub account
2. Klik "Add New Project"
3. Kies je `vacature-dashboard` repository
4. Klik "Deploy"

### Stap 5 – Klaar!
Vercel geeft je een link zoals `https://vacature-dashboard-xyz.vercel.app`  
**Deze link werkt altijd, ook volgende week, ook op je telefoon.**

---

## Vacatures automatisch vernieuwen

Het dashboard haalt nieuwe vacatures op elke keer dat je de pagina opent of op "Vernieuwen" klikt.

Wil je het écht automatisch laten updaten zonder dat je de pagina opent?  
Dan kun je een gratis service zoals **Cron-job.org** instellen die jouw dashboard-URL elke dag aanroept.

---

## Technische details

### RSS feeds die worden gebruikt
| Bron | Type |
|------|------|
| Indeed.nl | RSS feed (gratis) |
| Nationale Vacaturebank | RSS feed (gratis) |
| ITjobs.nl | RSS feed (gratis) |

### CORS proxy
Jobboards blokkeren directe verzoeken vanuit de browser. De tool gebruikt daarom  
`allorigins.win` als gratis tussenlaag. Als een bron niet laadt, valt het dashboard  
terug op realistische voorbeelddata zodat je altijd iets ziet.

### Voor productiegebruik
Voor dagelijks professioneel gebruik raden we aan:
- Een eigen backend (Node.js/Python) die de RSS feeds server-side ophaalt
- Of een abonnement op **JobFeed.nl** voor een volledige professionele vacature-API

---

## Vragen?
Neem contact op met Elevation Partners of vraag Claude om aanpassingen.
