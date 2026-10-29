# Légkörzés és csapadék – magyar animáció

A `23_WeatherPat.swf` magyar adaptációja, HTML-oldalba ágyazott helyi Ruffle JavaScript/WebAssembly lejátszóval. Az eredeti animáció működését őrzi meg; nem önálló HTML/JavaScript-újraírás.

## Használat

A GitHub Pages oldalon közvetlenül fut. Helyben Windows alatt az `inditas.cmd` indítja (Python 3 szükséges). Másik lehetőség: `python -m http.server 8000`, majd `http://localhost:8000/`. A HTML közvetlen, fájlként történő megnyitása helyett HTTP-kiszolgáló kell.

A lejátszás gomb elindítja és megállítja az éves ciklust. Az időcsúszkával és a léptetőgombokkal is változtatható az időpont. Az ITCZ, a légnyomás, a Hadley-cellák metszete, a csapadék és a feliratok külön kapcsolhatók.

- M: magas légnyomás; A: alacsony légnyomás.
- ITCZ: trópusi összeáramlási öv.
- A csapadék jelmagyarázata havi mennyiséget mutat, milliméterben.
- Az animáció szemléltető tananyag, nem aktuális időjárási térkép.

## Forrás és alkotók

Eredeti fájl: `23_WeatherPat.swf`, © 2003 Prentice Hall, Inc., A Pearson Company. Kivitelezés: CADRE design Pty Ltd. Az eredeti szerzők, szerkesztők és közreműködők névsora az Alkotók gombbal érhető el. Az adaptáció nem hivatalos Pearson-kiadás.

Az eredeti licencfeltételeket megtartottuk és magyarra fordítottuk; a teljes eredeti szöveget a `forditas.json` is tartalmazza. A licenc oktatási, a kísérő tankönyvet használó kurzushoz kapcsolódó felhasználást ír le. A fordítás nem terjeszti ki az eredeti engedélyt, és nem ad új licencet az eredeti műre.

Ruffle: MIT / Apache-2.0; a licencek a `ruffle` mappában találhatók.
