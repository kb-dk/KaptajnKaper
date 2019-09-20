# KaptajnKaper
Source Code of Peter Ole Frederiksens original Danish pirate game


Peter Ole Frederiksen klassiske piratspil, Kaptajn Kaper i Kattet til PC DOS 2.0 fra 1985, udgives her under en GNU General Public License version 3 licens i samarbejde med Peter Ole Frederiksens to sønner, Jan Thorhauge Frederiksen og Morten Frederiksen.
Kildekoden er doneret til Det Kgl. Bibliotek af Thorbjørn Stegelmann, som vi takker mange gange for at hjælpe med at sikre bevaringen af den digitale danske kultuarv for eftertiden.

Nedenfor er indholdet af Peter Ole Frederiksens egne instrukser fra disketten med spillets kildekode:


```
Dette er sourcekoden til Kaptajn Kaper i Kattegat.

Foruden denne file, skal disketten indeholde følgende:

BUILD.BAS
SKUD.BAS
TEGN.BAS
HLP.BAS
KAPER.BAS
SPECIAL.BAS
TITEL.PIC

Build opbygger kortet over Kattegat og BSAVE'er det.
Skud opbygger billedet til kamp med kanoner - herunder også det skib,
der bruges, når man border - og BSAVE'er det.
Tegn laver diverse plask og flag og gemmer dem i figure.dat
Hlp opbygger help-filen med skilletegn for ny side og nyt afsnit.
Kaper er selve hovedprogrammet.

Du kan udskrive programmet ved "print kaper.bas" eller editere det
direkte med personal editor eller lignende.

Special er en version, der kan køre uden at være blevet kompileret
med BASIC COMPILER, altså lavet til maskinkode.

Du må være klar over, at denne version af programmet kører MEGET langsomt,
men det kan du eventuelt selv rette i.

Som det vil kunne ses, er der gjort meget for at omgå pladsbegrænsninger
når der samtidigt skal være plads til to fulde get/put skærme i memory.

Alle programmerne ligger i ASCII-format på disketten, så de kan
editeres direkte. Til gengæld tager de lang tid at load'e ind i
basic, så hvis du vil, kan du loade dem og derpå save dem igen,
så de kommer til at ligge i normalt basic format, så loader de
hurtigere. Altså:
LOAD"SPECIAL
SAVE"SPECIAL

Hvis du vil bevare dem i ASCII-format, må du skrive:
SAVE"SPECIAL.BAS",A

Hvis der skulle være uklare punkter (der er jo ikke mange kommentarer),
så kontakt mig på 06-166511 om dagen eller 06-394185 om aftenen.


		Venlig hilsen

		P.O.Frederiksen
```
