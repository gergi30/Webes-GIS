#Webes GIS fejlesztés beadandó feladat

## A dokumentáció a következő részeket tartalmazza:

- Szerző
- Követelményanalízis
- Tervezés
- Implementáció
- Tesztelés

## Szerző
----------

- Név:		Nagy Gergely
- Neptun: 	JJSR78
- Dátum:	2015.02.22.


## Követelményanalízis
----------------------

### Funkcionális elvárások

A weboldal az alábbi címen érhető el: http://people.inf.elte.hu/gergi30/

Szabadon választható vektoros forrásokból valamint Excel vagy CSV formátumokkal együtt kell dolgozni. Feladatok:
 - Vektoros adatok importálása Google Fusion Table-be. ✓
 - Leíró adatok importálása Google Fusion Table-be. ✓
 - Adatokra vonatkozó szűrések elvégzése. ✓
 - HTML oldal elkészítése Bootstrap (ha szükséges Javascript használata) ✓
 - Fusion Table-ben elkészített térkép integrálása HTML oldalba. ✓
 - Felhasználói felületre vonatkozó tervezési tanácsok, ezen a linken elérhető ✓

### Dokumentáció:

A dokument az alábbi címen érhető el: https://github.com/gergi30/Webes-GIS

 - Beandó célja (milyen térképet szeretnénk elkészíteni, és mi a célja) ✓
 - Adatforrások megjelölése (formátum és forrás) ✓
 - Térbeli adatok osztályozása és szűrésére vonatkozó leírás. ✓
 
## Tervezés
-----------

### Beadandó célja

### Adatforrás

A csapatok adatait az ***http://www.nba.com/*** weboldalról gyűjtöttem.
Vesszővel elválasztótt CSV fájlba gyűjtöttem, majd ezt importáltam Google Fusion Table-be.

Táblázat első pár sora:

	Team name,URL logo,Championship wins,Address,Telephone,Fax,Latitude,Longitude
	Philadelphia 76ers,url,3,Wachovia Center 3601 South Broad Street Philadelphia PA 	19148,215-339-7666,215-339-7632,39.9010963,-75.17187430000001
	Boston Celtics,url,17,151 Merrimac Street Boston MA 02114,617-854-8000,617-523-5949,42.3641448,-71.0630112
	New York Knicks,url,2,Madison Square Garden Two Pennsylvania Plaza New York NY 	10121,212-465-6471,212-465-6498,40.7501303,-73.99257019999999


### Architektúra terv

#### Oldaltérkép:

A megoldott feladat cask egy html fájlt tartalmaz , ami több menüpontra tagolódik:

* fő oldal
	* Kezdőlap
	* Rólam
	* Napi idézet
	* Térkép
	* Kapcsolat

## Implementáció
-----------------

### Fejlesztői környezet bemutatása

	A fejlesztét a Notepad++ ingyenes forráskódú szoftverrel végeztem.
	Jellemzői:  kódkiemelés és kódblokkok egységbe zárása, felhasználó által állítható kódkiemelés, WYSIWYG felület
	
### Könyvtárstruktúrában lévő mappák funkiójának bemutatása
	

Könyvtár szerkezet:

    * ./css: css fájlok
    * ./fonts: betűtípusok
    * ./img: képek
    * ./js: oldalon használatos script fájlok

## Tesztelés
-------------



Made by Nagy Gergely :fire: :fire: :fire:
