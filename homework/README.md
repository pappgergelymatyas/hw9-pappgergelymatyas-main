# Házi feladat

1) Az órán használt `ess_9` adatbázist kell használni: az adatbázishoz való hozzáféréshez szükséges linket egy másik csatornán küldöm.
2) Ehhez a házi feladathoz nem lesznek tesztek, a megoldásokat a README.md fájl szerkesztésével tudjátok majd megadni. A válaszokhoz tartozó kódot töltsétek fel a githubra (de az adatot semmiképpen ne tegyétek fel)
3) Az egyes kérdéseknél a 7 vagy 8 (vagy 77 vagy 88) a nem tudja, nem válaszol kategóriákat rögzíti. Ezeket a minimum és maximum számolásnál ne vegyétek figyelembe

### Válaszoljátok meg a következő kérdéseket:

Az emberek általános boldogságát a `happy` változó méri (0-10-ig terjedő skálán): 
- Átlagosan mennyire boldogok a kérdőívet kitöltők? (egy szám)
- Mekkora a különbség a férfiak esetében a legalacsnyabb és a legmagasabb érték között? Hogyan alakul ez a nőknél? (a férfiakat 1-el a nőkket 2-vel jelöli az adatbázis) (egy egy szám)
- Készítsetek egy kategorikus változót a korból: 1 - 25 és az alatt, 2 - 26-45, 3 - 46-65, 4 - 66 és afelett
- Nézzétek meg, hogy a medián értékek ezekben a csoportokban hogyan alakulnak! (4 szám)  

A következő feladathoz a `dweight` változót fogjuk használni: *For advanced users who may want to model a nonresponse correction themselves we provide a design weight (dweight). This weight corrects only for differential selection probabilities. Please note that we do not recommend use of this weight without non-response correction.*

Készítsetek egy adatbázist, amiben csak azok szerepelnek, akik a dweight változóban 1-es értéket kapnak.
- Az `aesfdrk` változó azt méri, hogy mennyire érzi magát biztonságban a kérdezett a sötétben az otthona környékén (1-5-ig terjedő skála). Vizsgáld meg, hogy mennyiben tér el a szűrt és a teljes adatbázis esetén ennek a változónak a minimuma, maximuma, átlaga és mediánja. (4 szám amik a vizsgált dimenziók különbségét mutatják --> teljes adat - szűrt adat)

Keressetek még két számotokra izgalmas kérdést. Írjátok meg a kérdést is és a hozzá tartozó válaszokat is.

1. kérdés: 6.643546441495778
2. kérdés: 10, és ismételten 10.
3. kérdés: -
4. kérdés: 8.0 7.0 nan 7.0
