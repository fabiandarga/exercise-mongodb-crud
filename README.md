# MongoDB Crud
Diesmal wollen wir unsere Daten nicht nur lesen. 
Mit Hilfe der **mongo shell** können wir Dokumente hinzufügen, verändern oder löschen.

## Importiere den Datensatz "people.json"
* erstelle mit Compass eine neue Datenbank **test** mit einer Collection **animals**
* importiere dann die Datei **animals.json**

## Daten untersuchen
Schaue dir die Daten gründlich an.

## Füge neue Tiere hinzu
In der Liste wurden ein par Tiere vergessen, füge diese mit der hinzu:
```
    {
        "name": "Zippy",
        "kind": "Mouse",
        "favoriteFood": "Cucumber",
        "age": 2
    },
    {
        "name": "Fred",
        "kind": "Cat",
        "favoriteFood": "Cheese",
        "age": 4
    },
```
Antwort:
```
// Hier deine Lösung
```

## Alte Tiere finden und markieren
Die meisten Tiere werden nicht so alt wie Menschen.  
Wir wollen alle Tiere mit **"old": true** markieren, die schon **5 Jahre oder älter** sind.

Antwort:
```
// Hier deine Lösung
```

## Markiere die Vegetarier
Markiere alle Hasen, Mäuse, Vögel und Hamster (rabbit, mouse, bird, hamster) mit **"vegetarian": true**.

Antwort:
```
// Hier deine Lösung
```

## Tiere löschen
*Jack the Rabbit* und *Jack the Snake* sind sich leider zu nah gekommen. Lösche bitte Jack den Hasen (rabbit) aus der Liste.
Jack, die Schlange, soll natürlich nicht gelöscht werden.

Antwort:
```
// Hier deine Lösung
```