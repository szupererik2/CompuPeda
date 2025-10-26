# Hozzájárulás a CompuPeda projekthez

Köszönjük, hogy szeretnél hozzájárulni a CompuPedához!  
Ez a projekt közösségi kezdeményezés, amely nyíltan gyűjt pedagógiai és informatikai tananyagokat, hasznos forrásokat és feladatokat.

Kérjük, olvasd el az alábbi irányelveket, mielőtt beküldesz új anyagot vagy módosítást.

## Cél

A CompuPeda célja egy nyílt, magyar nyelvű tudásbázis létrehozása, amely
informatikai és pedagógiai tartalmakat gyűjt össze – például:

- ingyenes e-könyvek,
- hasznos weboldalak,
- tanulási segédletek,
- gyakorlófeladatok,
- jegyzetek, tananyagok.

Minden hozzájárulás segít abban, hogy a tudás elérhetőbbé váljon mindenkinek.

## Hogyan tudsz hozzájárulni?

Többféleképp segíthetsz:

- 🔗 Új források hozzáadása (pl. weboldal, könyv, feladat)
- 🧾 Meglévő tartalmak kiegészítése, frissítése
- 🧹 Hibák javítása (elírás, halott link, formázás)
- 💬 Ötletek megosztása a [Discussions](https://github.com/szupererik2/CompuPeda/discussions) vagy Issues fülön

Ha nem vagy biztos benne, hogy valami illik-e a projektbe, nyiss először egy *Issue*-t, és beszéljük meg.

## Mappa- és fájlstruktúra

A projekt a **00–99** sorszámozási rendszert követi.  
Minden fő kategória külön mappát kapott, pl.:

00_General/
10_Programming/
20_Math/
30_CS_Theory/
40_Useful_Sites/
50_Free_Ebooks/
99_Archive/

Egy-egy kategórián belül `.md` fájlokat használunk listák és leírások tárolására.  
A mappákban **ne hozz létre véletlenszerű új szinteket** — tartsd be a logikus hierarchiát (max. 5 mélységig).

## Tartalom formátuma

Minden új forrást **Markdown formátumban** adj hozzá, az alábbi sablont követve:

### [Forrás neve]

**Típus:** e-könyv / weboldal / kurzus / feladat / cikk  
**Leírás:** Rövid, 1–3 mondatos ismertetés magyarul.  
**Link:** [https://példa.hu](https://példa.hu)  
**Nyelv:** HU / EN / más

#### Példa

### Automate the Boring Stuff with Python

**Típus:** e-könyv  
**Leírás:** Ingyenes, gyakorlatorientált bevezetés a Pythonba, kezdőknek.  
**Link:** [automatetheboringstuff.com](https://automatetheboringstuff.com)  
**Nyelv:** EN

## Pull Request irányelvek

1. Készíts egy új *branch*-et a módosításaidhoz (`git checkout -b add-python-book`)
2. Ellenőrizd, hogy a tartalom illik-e a kategóriába
3. Tartsd be a Markdown formátumot
4. Egy PR-ben **csak egy témát** módosíts (pl. “új forrás hozzáadása”)
5. Adj hozzá leírást a PR-hoz: miért és mit módosítottál
6. Várd meg a review-t

Ha valami nem világos, nyugodtan kérdezz a *Discussions* részben!
