" # Datenaufbereitung und Visualisierung – Erneuerbare Energien in Bayern

Modularbeit im Fach *Datenaufbereitung und Visualisierung*, Hochschule München (Sommersemester 2026).

## Arbeitshypothese

> Der Anteil erneuerbarer Energien an der Stromerzeugung in Bayern ist höher als der deutsche Durchschnitt und wächst schneller.

Betrachtet als Anteil an der Stromerzeugung im Zeitraum **2000–2024**.

Bayern präsentiert sich gern als Vorreiter der Energiewende. Im Rahmen dieser Arbeit wird diese Aussage anhand offener Daten überprüft und in einer Infografik nachvollziehbar aufbereitet.

## Datengrundlage

| Datensatz | Quelle | Inhalt | Zeitraum / Format |
|---|---|---|---|
| Stromerzeugung Deutschland | [Our World in Data](https://ourworldindata.org/energy) (Datenbasis: Ember, Yearly Electricity Data) | Jährliche Stromerzeugung je Energieträger (Kohle, Gas, Öl, Kernenergie, Wasser, Wind, Solar, Bioenergie) in TWh sowie Anteile | 2000–2024, CSV |
| Bruttostromerzeugung Bayern | [Bayerisches Staatsministerium für Wirtschaft, Landesentwicklung und Energie](https://www.stmwi.bayern.de) (Energiebilanz) | Jährliche Stromerzeugung je Energieträger in GWh sowie Anteile | 2000–2024, XLSX |

Erneuerbare Energien = Wasserkraft + Wind + Solar (PV) + Bioenergie.

Alle Rohdaten liegen im Ordner [`data/`](./data).

## Projektstruktur

├── data/ # verwendete Rohdatensätze (CSV, XLSX)

├── dataviz.Rmd # R-Markdown-Analyse (Datenaufbereitung, Exploration, Visualisierung)

├── dataviz.html # kompilierter Report (Ergebnis von dataviz.Rmd)

└── README.md

## Verwendete Tools

- **R** mit [R Markdown](https://rmarkdown.rstudio.com/)
- Pakete aus dem [Tidyverse](https://www.tidyverse.org/): `ggplot2`, `dplyr`, `tidyr`, `readr`, `readxl`, `stringr`, `forcats`, `lubridate`, `purrr`, `scales` "

## Report ansehen

Die interaktive Visualisierung ist online abrufbar unter:
**https://parinazsh99-blip.github.io/dataviz-analysis-r/dataviz.html**

Alternativ: Den vollständigen, kompilierten Report inklusive aller Visualisierungen findest du in [`dataviz.html`](./dataviz.html) – lokal herunterladen und im Browser öffnen.

Um den Analyse-Code selbst auszuführen: `dataviz.Rmd` in RStudio öffnen und knitten (benötigte Pakete werden beim ersten Lauf ggf. installiert).

## Autorin

Fatemeh Shafiee – Hochschule München, Sommersemester 2026
