# LIVE DEMO:

## Page-fil:

- Strukturen er veldig nære vanlig html, men med noen endringer
- "Frontmatter", kan bruke js som skjer når sida genereres, fetch-kall, e.l.

## Components:

- Vise frem Number-component
- Poengtere at jeg bruker en div selector, styling er by default lokal, og applier bare til html i samme komponent
  - Kan vise hvordan både is:inline og is:global funker ved å gå til dev tools -> Sources -> src/numbers
- Ta den i bruk i numbers-sida (har backup)
- Vise frem Layout, forklare hva layouts er
  - er components på samme måte som Card, men er en vanlig konvensjon, har typisk hvertfall html, head og body elements (ofte mer).
  - Nevne slot
  - Ta i bruk Layout

## Interactivity og scripts:

- Prøv å lage en button som refererer til funksjonen i frontmatteret, vis at det ikke funker

  - Vis at alert ikke er definert - dette er ikke kode som kjører i browseren
  - (frontmatter eksisterer bare på serveren)

- Kopier ned tallene og flytt funksjonen til en script tag, vis at det fortsatt ikke funker, men at det nå funker med en alert.

  - Dette er kode som blir bundlet som en js-modul som importeres på sida. JS kjøres derfor, men kan ikke refereres til i htmlen direkte (måtte brukt en eventhandler)
  - legg på is:inline for å vise at script-tagen da havner i koden på vanlig måte

# TILBAKE TIL SLIDES

- client-direktiver
- Støtte for andre rammeverk
- Støtte for andre verktøy

Nå er vi på punktet der Astro virkelig blir awesome for content-driven sites

- MD-støtte
- Content collections
