# Esimene projekt

## Projekti ülevaade

See projekt on kriisivalmiduse veebisait nimega **VALMIS**. Veebilehe eesmärk on aidata kasutajal valmistuda kriisiolukordadeks, näiteks robotite, droonide, elektrikatkestuse, sidekatkestuse ja evakuatsiooni korral.

Veebilehe kujundus valmis Figma abil. Pärast kujunduse tegemist kirjutasime selle HTML-i ja CSS-iga veebileheks.

## Figma disain

Projekti algne kujundus on loodud Figmas:

[Esimese projekti Figma disain](https://www.figma.com/design/x6w2541fYStYgNwth228rB/Esimene-projekt?node-id=0-1&t=xQojhKYPcMVH6vNy-1)

## Projekti tegemine

### Esimene päev

Esimesel päeval alustasime veebisaidi disaini kavandamisega. Tegime Figma abil valmis esimesed kujunduse osad ning panime paika veebilehe üldise stiili, värvid ja paigutuse.

### Teine päev

Teisel päeval lõpetasime suurema osa Figma disainist. Seejärel hakkasime kujundust koodiks muutma. Iga grupiliige vastutas projekti erineva osa eest:

- **Kevin** tegi `index.html` lehe ehk veebisaidi avalehe.
- **Trevor** tegi `juhendid.html` lehe ehk kriisiolukordade juhendid.
- **Rasmus** tegi `list.html` lehe ehk kriisivarude kontrollnimekirja.

Teise päeva lõpuks saime suurema osa veebisaidi koodist valmis.

## Failide struktuur

```text
esimene-projekt/
├── index.html
├── juhendid.html
├── list.html
├── css/
│   ├── style.css
│   ├── juhendid.css
│   └── list.css
├── images/
│   ├── drone.png
│   ├── turret.png
│   └── technology.png
└── README.md
```

## Leheküljed

### `index.html`

`index.html` on veebisaidi **avaleht** ehk esimene leht, mida külastaja tavaliselt näeb. Faili nimi `index.html` on veebiprojektides tavapärane, sest veebiserver otsib sageli just seda faili vaikimisi avalehena.

Avalehel on:

- veebisaidi pealkiri ja sissejuhatus;
- ülevaade robotite, droonide ja tehnoloogiliste häiretega seotud ohtudest;
- lingid juhendite ja kriisivarude lehele;
- ettevalmistuse ja ohutuse sektsioonid.

Selle lehe kujundust määrab `css/style.css`.

### `juhendid.html`

See leht sisaldab juhiseid erinevates kriisiolukordades käitumiseks. Juhendid on jaotatud teemadeks:

- robotite ja droonide oht;
- elektrikatkestus;
- sidekatkestus;
- küberrünnak;
- evakuatsioon.

Selle lehe kujundust määrab `css/juhendid.css`.

### `list.html`

See on kriisivarude ja tegevuste kontrollnimekiri. Kasutaja saab märkida ülesanded tehtuks märkeruutude abil. Lehel olev JavaScript arvutab märgitud punktide põhjal ka edenemise protsendi.

Selle lehe kujundust määrab `css/list.css`.
