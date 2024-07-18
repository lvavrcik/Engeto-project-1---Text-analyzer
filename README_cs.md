# Engeto-project-1---Text-analyzer
Kód pro 1. Engeto projekt - Textový analyzátor

# Textový analyzátor #

## Popis projektu ##
Cílem tohoto projektu je vytvořit textový analyzátor - program, který se bude umět prokousat libovolně dlouhým textem a zjistit o něm různé informace.

**Popis programu**: 
- program si vyžádá od uživatele přihlašovací jméno a heslo
- zjistí, zda vložené údaje odpovídají údajům registrovaných uživatelů (viz níže, **Registrovaní uživatelé**)
- pokud je uživatel registrovaný (jsou vloženy správné údaje), program uživatele pozdraví a vyzve ho k analýze textů
- pokud uživatel není registrovaný (jsou vloženy nesprávné údaje), program jej upozorní a ukončí se

- program nechá uživatele vybrat mezi třemi texty, uloženými v proměnné TEXTS (viz níže, **Texty k analýze**):
    - pokud uživatel vybere takové číslo textu, které není v zadání, program jej upozorní a skončí
    - pokud uživatel zadá jiný vstup než číslo, program jej rovněž upozorní a skončí

- pro vybraný text spočítá následující statistiky:
    - počet slov
    - počet slov začínajících velkým písmenem
    - počet slov psaných velkými písmeny
    - počet slov psaných malými písmeny
    - počet čísel (ne cifer)
    - sumu všech čísel (ne cifer) v textu

- program zobrazí jednoduchý sloupcový graf, který bude reprezentovat četnost různých délek slov v textu

## Texty k analýze ## 
**TEXT 1**: Situated about 10 miles west of Kemmerer,
Fossil Butte is a ruggedly impressive
topographic feature that rises sharply
some 1000 feet above Twin Creek Valley
to an elevation of more than 7500 feet
above sea level. The butte is located just
north of US 30N and the Union Pacific Railroad,
which traverse the valley.

**TEXT 2**: At the base of Fossil Butte are the bright
red, purple, yellow and gray beds of the Wasatch
Formation. Eroded portions of these horizontal
beds slope gradually upward from the valley floor
and steepen abruptly. Overlying them and extending
to the top of the butte are the much steeper
buff-to-white beds of the Green River Formation,
which are about 300 feet thick.

**TEXT 3**: The monument contains 8198 acres and protects
a portion of the largest deposit of freshwater fish
fossils in the world. The richest fossil fish deposits
are found in multiple limestone layers, which lie some
100 feet below the top of the butte. The fossils
represent several varieties of perch, as well as
other freshwater genera and herring similar to those
in modern oceans. Other fish such as paddlefish,
garpike and stingray are also present.

## Registrovaní uživatelé ##
user |   password

bob  |     123 

ann  |   pass123

mike | password123

liz  |   pass123




