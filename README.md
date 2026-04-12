# HaDiKo Geländeplan

![Plan des Gelände des HaDiKos](./HaDiKo%20Plan%20Export.svg)

_Geländeplan des HaDiKos_

## Anforderungen

- Inkscape (zuletzt bearbeitet mit v1.4)
- Schriftarten:
  - Open Sans
  - Roboto

## Zusätzlichen Informationen

- Schatten
  - Offset
    - x: 9mm, y: 3mm
  - Damit Schatten in Inkscape richtig gerendert werden können,
    muss in den Einstellungen (Bearbeiten > Einstellungen > Rending)
    "Filter effects quality" auf "Best quality" gesetzt werden
- Texturen
  - Texturen sind als JPGs mit 60% Qualität eingebettet
  - Parkplätze sind mit Array-Effekten realisiert

## Export

Um den Plan in externen Quellen einzubinden, die möglicherweise die obigen Schriftarten nicht haben, muss wie folgt vorgegangen werden:

- eine Kopie der Datei als `HaDiKo Plan Export.svg` speichern
- in dieser Kopie alles auswählen
- unter `Pfad > Objekt in Pfad umwandeln`
- speichern

Dann sind alle Schriften als Pfade gespeichert und werden überall korrekt angezeigt.
