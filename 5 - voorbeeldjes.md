# DEMO 5 - Voorbeeldjes!

Hier zie je voorbeeldjes om je op ideeën te brengen. 

Op de volgende pagina zie je een compleet overzicht van alle mogelijkheden.

## Moire-patroon

<iframe style='float: right' src="https://coderdojo-leiden.github.io/demos-digitale-kunst/voorbeeld/moire/"></iframe>

We maken een `Lijnen` laag (die lijnen van links naar rechts over het hele scherm tekent), dan maken we een kopie van die laag en die kopie laten we langzaam heen en weer draaien.

```js
laag(Lijnen)
wijzig("kleur", "zwart")

kopieer_laag()   // maak nog een Lijnen laag door de vorige te kopiëren
laag(Draai)
wijzig("hoek", getal.golf(50, 20))
```

<div style="clear:both"></div>

### Tekstrol

<iframe style='float: right' src="https://coderdojo-leiden.github.io/demos-digitale-kunst/voorbeeld/tekstrol/"></iframe>

We maken een `Tekstrol` laag en zetten onze eigen tekst er in. Als je enkele omgekeerde aanhalingstekens gebruikt (\` linksboven op je toetsenbord), kun je je tekst over meerdere
regels verdelen. We laten de tekst golven met de `hoogte` eigenschap. Probeer ook `zigzag` en `puls` eens in plaats van `golf`!

```js
laag(Tekstrol)
wijzig("tekst", `
Dit is een tekstrol.
Je kunt hier je eigen tekst zetten.
Hij kan zo lang worden als je wilt.
Doei..................!
`)
wijzig("kleur", "zwart")
wijzig("lettertype", "boek")
wijzig("hoogte", getal.golf(20, 40))
```

<div style="clear:both"></div>

### Nog veel meer mogelijkheden

Experimenteer zelf verder! Als je echt alle mogelijkheden wilt weten: kijk in het [overzicht in de volgende stap](./6%20-%20meer%20mogelijkheden.html).

<p style='font-size: 150%; font-weight: bold; text-align: right;'>
    <a href='./6%20-%20meer%20mogelijkheden.html'>Volgende stap <img style='margin: -0.4em 0.5em; float: right; width: 10%' src='images/arrow.png'></a>
</p>