---
title: Stage werkplan (PvA)
subtitle: CCS DC Snel laadden van PEVs bij EV Europe
author: Luca van Straaten (SN:10873611)
date: \today{}
documentclass: scrreprt
papersize:
- a4
fontsize:
- 11pt
geometry:
- margin=1in
fontfamily:
- charter
numbersections: false
header-includes:
- \setlength\parindent{24pt}
output:
  pdf_document:
    latex_engine: xelatex
...

\pagenumbering{roman}
\clearpage
\tableofcontents
\clearpage
\pagenumbering{arabic}
\setcounter{page}{1}

# Wat doet EV Europe?

Volgens de wersite van [EV Europe](https://eveurope.eu/about/):

>EV Europe is een fusie tussen twee toonzettende marktleiders op het gebied van
>elektrisch rijden: Heijnsdijk Electric Cars en EV Custom. Elk met een eigen,
>uniek segment en de daarbij behorende ervaring; Heijnsdijk Electric Cars
>richtte zich op de levering, ontwikkeling en certificering van EV componenten
>en Lithium accusystemen, EV Custom richtte zich op complete projecten voor
>klanten die een full-service concept wensten. Vanwege de verregaande en unieke
>expertise, de juiste klik en gedeelde passie voor elektrisch rijden en
>duurzaamheid besloten de eigenaren van beide bedrijven Vincent Heijnsdijk en
>Peter-Jan Schouten begin 2018 te fuseren tot EV Europe. Met de oprichting van
>EV Europe ontstond de marktleider op het gebied van elektrische mobiliteit en
>lithium accusystemen volgens een one-stop-shop concept.

# Wat ga ik doen bij EV Europe?

## Achtergrond informatie

Het laden van een EV (elektrisch voertuig) gaat in Europa met het CCS (Combined
Charging System). Dat is een standaard voor het laden van een EV die de
connector beschrijft, de communicatie tussen de EV en de lader (EVSE) is
gedefinieerd in ISO 15118. CCS ondersteunt zowel AC laden (op een of drie
fasen) als DC laden, DC laden heeft het voordeel dat het laden sneller kan.
Momenteel gebruikt EV Europe een simpel laadsysteem dat alleen met AC werkt.

## Wat ik ga doen

Ik ga aan een ECU (Electronic control unit) werken die de CCS communicatie gaat
doen volgens ISO 15118 tussen de EV en de EVSE (Electric vehicle supply
equipment), zodat EV Europe apertuur kan leveren waarmee klanten hun EV kunnen
snelladen.

# Eisen van het project

Het eindresultaat is een werkend CCS-systeem, dat zowel AC (een of drie fasen)
als DC moet kunnen laden. Voor dit project dient het te werken op een
testopstelling van EV-europe. De testopstelling kan woorden meegenomen naar een
CCS DC EVSE om te testen. Het systeem moet zo woorden uitgewerkt dat het
ingebouwd kan worden in nieuwe en bestaande EV-conversies.

Exacte technische eisen worden uitgewerkt in het eindverslag.

# Hoe is het eindverslag (stageverslag) ingedeeld

1.  Samenvatting
2.  Inleiding
3.  Analyse van het probleem
4.  Eisen van het project
5.  Mogelijke oplossingen
6.  De gekozen oplossing
7.  Ontwerp van de oplossing en de benodigde onderdelen
8.  Assemblage van de oplossing
9.  Problemen tijdens implementatie
10. Eindresultaat
11. Toetsing eindresultaat aan de hand van de eisen
12. Conclusie en aanbevelingen
13. Evaluatie
14. Bronnen
15. Bijlagen

Ook onderdelen als een voorblad en inhoudsopgave. Deze indeling is onder
voorbehoud en kan gewijzigd worden.

# Aanpak

Eerst ga ik onderzoek doen naar wat de exacte eisen en verwachtingen zijn van
de te ontwerpen elektronica en wat de prioriteiten zijn. Vervolgens ga ik
onderzoeken waar ik tegen aan kan lopen. Daarna ga ik de test opstelling prepareren en
mechanisch in orde maken. De volgende stap is het ontwerpen van de elektronica.
En een prototype hiervan maken. Daarna kan ik dat gaan testen, en
veranderingen doorvoeren naar de uiteindelijk versie van het product. Tijdens
het gehele traject zal ik mijn bevindingen documenteren in het eindverslag.

## Stappen om het eindresultaat te behalen

*   onderzoek doen naar de mogelijkheden
*   kiezen welken mogelijkheden getest gaan woorden
*   ontwerpen van de elektronica
*   assemblage wan de testopstelling(en)
*   testen van de testopstelling, en problemen oplossen
*   documentatie schrijven

Tegelijkertijd met de bovengenoemde stappen zal ik deze documenteren in het
verslag

#  Planning van werkzaamheden met tijdschema

Hier staan onder anderen de eerder genoemde stappen in vermeld.

### werkweek 1
*   Achtergrondinformatie onderzoek
*   informatie over

### werkweek 2
*   Werken aan PvA

### werkweek 3
*   testopstelling gereed maken

### werkweek 4
*   werken aan de testopstelling

### werkweek 5
*   testen van verschillende oplossingen

### werkweek 6
*   oplossing kiezen

### werkweek 7
*   testen van gekozen oplossing

### werkweek 8
*   rapport met productiemethode

### werkweek 9
*   uitloop

### werkweek 10
*   Afronden en inleveren eindverslag

# Wat zijn de verwachten (technische) resultaten van het project

Er moet een prototype opstelling woorden gemaakt, van een CCS DC Snellaad
systeem. het is de bedoeling dat deze in een EV-conversie kan woorden
ingebouwd, dus er moet gedocumenteerd woorden hoe dat zou kunnen.

Een werkende testopstelling, documentatie over hoe het werkt en over hoe het
geproduceerd is/moet woorden, is het doel van de opdracht, en dus ook de
verwachte resultaten van het project.

# Te behalen competenties

Volgens de studie wijzer zijn de competenties waar aan moet worden gewerkt:
Analyseren, Ontwerpen, Managen en Onderzoeken. Ik denk ook dat daar het meesten
van mijn tijd in gaat zitten

Ik hoop op al deze gebieden te groeien en zal daar in het eindverslag verslag
van doen.
