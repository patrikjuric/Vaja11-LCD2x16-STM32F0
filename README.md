# Vaja11-LCD2x16-STM32F0

 Najprej za RS in E priključka na LCD zaslonu izbereva in aktivirava pina PB5 in PB10 kot GPIO_Output. Tudi za priključke D4 do D7 na LCD zaslonu aktivirava 4 pine PC7, PA9 , PA7 in PA6 kot GPIO_Output.V Clock Configuration spremeniva frekvenco na vrednost, da bo polovica najvišje možne: Nova frekvenca bo 40 MHz. Nastavljena hitrost podatkov na vodilih(max. output speed) je LOW. Min ter max vrednosti za x in y za LCD zaslon so x y 207 144 316 146 255 154 242 155 234 157. 
 Funkcija itoa spremeni int v string uporabiti jo moramo da lahko beremo tudi decimalne in hexadecimalne vrednosti.
 
 KOMENTAR NA DELOVANJE:
Naloga deluje po navodilih, na LCD zaslonu se izpisuje napis STPŠ in pa številke od 1 do 9.
