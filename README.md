# Phone company site
Projekt für Test im UI Modul

- Schreib das HTML und CSS für die abgebildete Seite
- Die Seite soll responsive sein und sich auf unterschiedlichen Bildschirmbreiten entsprechend der Abbildungen verhalten.

## Anforderungen HTML
- Die Seite soll auf dem Handy bzw. im DevTools-Simulator nicht kleiner skaliert/kleiner gezoomt werden.
- Einrückung der Kinder-Elemente im Code
- Korrekte Dateipfade
- Beschreibende Klassen- oder ID-Namen für Elemente vergeben
## Anforderungen CSS
- Selektoren so speizifisch schreiben, dass unabsichtliche Auswirkungen auf andere Teile der Seite vermieden werden.
- Kein float zum Anordnen von Block-Elementen
- Style-Werte, die sowieso standardmäßig vom Browser gesetzt werden, nicht im CSS deklarieren.

![](drafts/mobile.JPG)
![](drafts/tablet.JPG)
![](drafts/desktop.JPG)
![](drafts/desktop-button-hover.JPG)

###   20/60 Punkten
#### Punktabzüge für:
- [x] (10) Elemente passen sich nicht an Fensterbreite an
```diff
- Die Text-Blöcke im Jumbotron werden bei manchen Fendtergrößen zu schmal
```
- [_] (10) Tags nicht geschlossen oder falsch verschachtelt
- [_] (5) Block-Tag in Inline-Tag
- [_] (5) Kinder-Tags im Code nicht eingerückt
- [x] (10) Zweckfremde Tags verwendet
```diff
- Die verwendeten Bootstrap-Klassen lassen die 
```
- [_] (10) Fehlende essetielle Tags (z.B. Meta-Tags)
- [x] (5) Falsche Datei-Pfade
```diff
- Die style.css und die Bilder werden nicht geladen
```
- [x] (10) CSS-Selektoren, die bei Änderungen im HTML sehr leicht fehlschlagen können
```diff
- Die Verwendung von Inline-CSS für den button ist unnötig
```
- [x] (5) Fehlende essentielle Tag-Attribute
```diff
- img tag hat kein alt-Attribut
```
