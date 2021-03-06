DESIGNDOKUMENT, KOLADAPP
========================

Grundläggande beskrivning
-------------------------
KoladApp ska vara ett verktyg för visuell och numerisk analys av data ur Kolada.

(I en framtida version är även annan kommunuppdelad data en tänkbar kandidat för inkludering i appen, men inför v1.0 ligger fokus enbart på Kolada-data.)

Funktionalitet
--------------
Appen ska bestå av ett simplistiskt interface som möjliggör en begränsad uppsättning av analyser av data. Datat ska bestå av en så stor del av Kolada-data som möjligt. I en första testversion ingår en delmängd av datat med ett mindre antal variabler, årtal och kommuner.

Utöver själva appen ingår utvecklingen av verktyg (skript) för att läsa in exporterad Kolada-data, samla denna i en databas/fil (coldbir?) och läsa ur denna. Uppläsning av data sker helst on-the-fly.

**Förslag på funktioner**
- Tidsserieplot av en eller flera variabler för en eller flera kommuner
	-- Slicing
	-- Animation
- Jämförelse av två olika variabler över tid och/eller kommun
	-- Slicing
	-- Animationer
- Integration av klusteranalys/faktoranalys för data mellan kommuner givet en tidpunkt/tidsperiod
	-- Slicing
- Trädanalys av vissa variabler
	-- Geografisk och bakgrundsdata
	-- 
- Numerisk analys av variabler (standardiserade statistiska mått)
- Stories för ett visst år eller en viss kommun
- Plottning på karta av en eller flera variabler (både Sverige- och regionkartor)
- Top-vs-bottom-jämförelser
- Tips om intressanta variabler att jämföra, gärna automatiserat
- Dokumentation av variablerna
- Länkar till blogg, vägledningar etc. samt Kolada självt

Interface
---------
**Exempel på avdelningar/avgränsade funktioner:**
- Analysera en variabel
-- Grafisk illustration av en variabel
-- Spridningsmått
-- Annan deskriptiv statistik
- Analysera flera variabler
-- Grafisk illustration av flera variabler
-- Sambandsmått mellan flera variabler
-- 

