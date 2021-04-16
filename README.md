# Aggregierte Covid-Fallzahlen pro Gemeinde

Visualisierung der bestätigten Covid Fällen pro Gemeinde


Vom BAG am 13.04.2021 erhaltene Daten: [publishable_data_cum_20210413.csv](publishable_data_cum_20210413.csv)

* Phase 1: 24.2.2020 – 7.6.2020 – 104 Tage
* Phase 2: 8.6.2020 – 24.2.2021 – 261 Tage
* Phase 3: 25.2.2021 – 9.4.2021 (heute) – 47 Tage

Datenstand: 13.04.2021

Population ist angehängt, Gemeindestand ist 2021, die kat_cum ist die kumulative Inzidenz pro 1000 Einwohner normiert auf 14 Tage – d.h. 1000 * (Fälle/Pop)*(14/Anzahl Tage in Phase).

Die Werte sind auf 14 Tage normieren, weil sich die Phasen in der Länge unterscheiden.

Die Kategorien sin  nach Jenks berechnet, 7 Kategorien.

Die Daten wurden basierend auf einem [Skript der NZZ](https://github.com/nzzdev/st-methods/tree/master/2013%20Corona-Gemeindedaten) aggregiert, welches ebenfalls auf Github einsehbar ist. 
