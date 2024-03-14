# Introduktion till programmering i Python - DVG017 
# Uppgift - Projekt 2.5 hp
Du ska skapa ett textbaserat spel där både skicklighet och tur krävs för att vinna.
Användaren blir inlåst i ett hus med zombies och enda sättet att ta sig ut är att svara rätt på matematiska frågor och välja rätt dörr för att undvika att bli uppäten av zombiesar.

Antal frågor ska vara 12 och varje fråga består av två delar, först måste användaren svara rätt på en matematisk fråga och sedan välja rätt dörr för att undvika zombiesarna.

Alla matematiska frågor har räknesättet multiplikation.
Spelare väljer vilken tabell (2 - 12). Valet av tabell görs en gång och sedan kommer alla frågor att vara på den tabellen.
Den matematiska frågan ska vara, faktor * tabell, där faktorn slumpas fram (0 - 12).
Användaren gissar vad produkten blir.
Samma matematiska fråga får inte förekomma flera gånger. 

Spelet börjar med att användaren svarar på en matematisk fråga, om användaren svarar rätt, ska användaren välja en dörr av flera och undvika zombiesarna som finns bakom en av dörrarna. Antal dörrar motsvarar antal frågor, när antalet frågor är 12 ska första gången val av dörr presenteras vara 12 dörrar varav zombiesarna finns bakom en av dörrarna, på fråga två är antalet dörrar 11 osv, tills näst sista frågan då antalet dörrar är två. 
Oavsett antal dörrar är det alltid bakom en av dörrarna zombiesarna gömmer sig.
På sista frågan kommer inte frågan om dörrar, utan där räcker det med att svara rätt på frågan för att vinna.

Inmatning från användaren kan antas vara ett heltal och inom korrekt intervall.

Om användaren svarar fel på en matematisk fråga eller väljer fel dörr förloras spelet. Användaren vinner spelet när alla frågor besvarats korrekt.

Användaren ska hela tiden veta hur långt hen kommit i spelet, dvs hur många frågor som hen har klarat hittills och hur många frågor som är kvar.
När användaren gissar på en korrekt dörr, dvs där inte zombiesarna gömde sig, ska användaren meddelas om vilken dörr zombiesarna var bakom.

Vid spelet slut, oavsett vinst eller förlust, ska en fråga om ett nytt spel visas.
