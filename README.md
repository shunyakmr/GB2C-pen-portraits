# Supplementary Material: Pen Portraits

**Beyond aggregate spending: a behavioural typology of online gambling and its neighbourhood patterning in Great Britain**

Dr Shunya Kimura | University of Liverpool | s.kimura@liverpool.ac.uk

## Overview

This repository contains the supplementary material for the accompanying research paper (work in progress, March 2026). It provides detailed pen portraits for each of the 12 behavioural Types, plus a residual Others category, identified through a hierarchical classification of online gambling behaviour in Great Britain.

The 11 Active Types are organised into three activity Groups, alongside a Dormant Type and an Others category:

- **Betting-and-Gaming (BG)** — BG1–BG6
- **Betting-Exclusive (B)** — B1–B2
- **Gaming-Exclusive (G)** — G1–G3
- **Dormant**
- **Others** (estimated only at LSOA level)

Each pen portrait describes the distinctive gambling patterns, demographic composition and neighbourhood associations of a given Type. Interactive treemap figures allow navigation between Types, and links to the [Geographic Data Service (GeoDS)](https://mapmaker.geods.ac.uk/#/gambling-behaviours) provide interactive maps for each Type.

## Rendering

This project uses [Quarto](https://quarto.org). To render the HTML document:

```bash
quarto render
```

The output will be generated in the `_output/` directory.

### Requirements

- [Quarto](https://quarto.org/docs/get-started/) (>= 1.3)
- R with the following packages:
  - `plotly`
  - `htmlwidgets`
  - `ggplot2`

## Repository Structure

```
├── _quarto.yml    # Quarto project configuration
├── index.qmd      # Main document source
├── styles.css     # Custom styling (justified text)
└── _output/       # Rendered HTML output (git-ignored)
```

## Licence

All rights reserved. This material is provided as a supplement to a research paper in preparation. Please contact the author for permissions.
