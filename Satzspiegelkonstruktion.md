Satzspiegelkonstruktion
=======================

Vorgaben
--------

linker Rand:  35  
rechter Rand: 25  
oberer Rand:  25  
unterer Rand: 12.5  
(in mm; aus Projektbericht-Vorlage.docx; Einzelseite oder rechte Seite angenommen)

=> Satzspiegelbreite: 210 - 35 - 25 = 150


Berechnung für Teilung
----------------------

Vgl. [Rasterteilung](https://de.wikipedia.org/wiki/Satzspiegel#Rasterteilung), [Neunerteilung](http://archiv.dante.de/tex/typographie/satzspiegel/#x1-50016)

Vorgaben für oberen und unteren Rand werden ignoriert.

BS + 1 DIV + ?? DIV + 2 DIV = Seitenbreite  
(BS: Bundsteg, DIV: Feld in Raster)

rechter Rand = 2 DIV  
=> 1 DIV = 12.5  
=> Satzspiegelbreite = 12 DIV  
=> Bundsteg = 22.5

=> BS + 1 DIV + 12 DIV + 2 DIV = Seitenbreite  
=> 22.5 + 15 DIV = Seitenbreite

=> oberer Rand = 1 DIV = 12.5  
=> unterer Rand = 2 DIV = 25  
=> linker Rand = BS + 1 DIV = 35  
=> rechter Rand = 2 DIV = 25


Raster
------

```
     | BS |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 | 10 | 11 | 12 | 13 | 14 | 15 |
_____ _______________________________________________________________________________
     |                                                                               |
     |                                                                               |
___1_|          ___________________________________________________________          |
     |         |                                                           |         |
     |         |                                                           |         |
___2_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
___3_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
___4_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
___5_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
___6_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
___7_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
___8_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
___9_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
__10_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
__11_|         |                                                           |         |
     |         |                                                           |         |
     |         |                                                           |         |
__12_|         |                                                           |         |
     |         |                                                           |         |
     |         |                            150                            |         |
__13_|         |___________________________________________________________|         |
     |                                                                               |
     |22.5|12.5|                                                           |    25   |
__14_|                                                                               |
     |                                                                               |
     |                                      210                                      |
__15_|_______________________________________________________________________________|

     | BS |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 | 10 | 11 | 12 | 13 | 14 | 15 |
```
