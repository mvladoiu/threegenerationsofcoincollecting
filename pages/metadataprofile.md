---
title: Metadata Application Profile 
layout: about
permalink: /metadataprofile.html
---

<h1>Metadata Application Profile</h1>     
<br>
<br>
The following elements are available for use: Object ID, Filename, Title, Format, Latitude, Longitude, Date, Location, Issuer, Lettering, Description, Type, Collector, Currency, Denomination, Size, Material, Symbol, Status, and Subject. 
<br>
<br>
The metadata for this library followed the following guidelines:
<br>
<br>
Object ID, Filename, Title, and Format were all formatted according to the requirements of [Collection Builder](https://collectionbuilder.github.io/cb-docs/docs/metadata/gh_metadata/). 
<br>
<br>
Latitude and longitude for map functionality were found at [Public Data](https://developers.google.com/public-data/docs/canonical/countries_csv) 
<br>
<br>
Date followed ISO format "yyyy". When possible, the date was taken directly from the coin or banknote. For the banknotes that didn't have dates, research was ddone to find when the notes were printed and a range was given, if necessary. 
<br>
<br>
Location uses naming conventions from the [Getty Thesaurus of Geographic Names Online](https://www.getty.edu/research/tools/vocabularies/tgn/).
<br>
<br>
Issuer refers to the governing body that issued the currency. In most cases, it is the same as location. It also follows naming conventions from the [Getty Thesaurus of Geographic Names Online](https://www.getty.edu/research/tools/vocabularies/tgn/)
<br>
<br>
Lettering gives a transcription of words on the coin/banknote.
<br>
<br>
Description tells what images are found on the coin/banknote.
<br>
<br>
Type describes if the item is a coin or banknote.
<br>
<br>
Collector refers to the person to whom the coin belongs, as the collections existed at the time of the library's creation. Written as first name, last name.
<br>
<br>
Currency gives the [ISO 4217 code](https://en.wikipedia.org/wiki/ISO_4217) for the currency and the common name. In cases where an ISO code does not exist, only the common name is given. 
<br>
<br>
Denomination gives the numerical value and name of the unit, which may be the same as the common name of the currency or may be a subunit. 
<br>
<br>
Size gives width x height in millimeters for banknotes and the diameter in millimeters for coins.
<br>
<br>
Material describes what the item is made out of; either paper or the specific metal used.
<br>
<br>
Symbol gives the graphic symbol denoting a currency. Symbols were found at [XE Symbols](https://www.xe.com/symbols/) and [Unicode](https://unicode.org/charts/PDF/U20A0.pdf) 
<br>
<br>
Status has the options of current or historical. In some cases, the name is the same or very similar, however this refers to whether or not the coin or banknote is current legal tender. See [Glossary](https://mvladoiu.github.io/threegenerationsofcoincollecting/glossary.html) for more information. 
<br>
<br>
Subject is a concise list of people, places, objects, animals, etc. that are depicted on the coin or banknote. 
<br>
<br>
All elements are required, however in some cases it might require an estimate or alternative (i.e. inexact dates, lack of ISO currency code, lack of official symbol). All elements are non-repeating, although subject can have multiple values separated by commas.
