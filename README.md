# Bird Sightings at Sea

## The Robins: Sydney Kahn & Jacqueline Adelmann

Math 244 Final Project

## Introduction

The dataset, *Bird Sightings at Sea* was sourced from [TidyTuesday](https://github.com/rfordatascience/tidytuesday/blob/main/data/2026/2026-04-14/readme.md), and originally comes from survey data collected at ports near New Zealand from 1969-1990. Each observation is a 10 minute session where bird sightings, sea state, weather, and location were recorded. The following codebook represents the variables of importance with respect to our project.

### Codebook

| Variable | Type | Description |
|-------------------|-------------------|----------------------------------|
| `species_family` | character | Bird family, created by grouping species |
| `count` | integer | Number of birds counted in the observation |
| `feeding` | logical | Birds observed feeding |
| `flying_past` | logical | Birds observed flying past the ship |
| `following_ship` | logical | Birds observed following the ship |
| `cloud_cover` | ordered | "clear", "partially cloudy" or "overcast" |
| `season` | ordered | Southern hemisphere season |
| `precipitation` | factor | Precipitation type, including levels of rain, snow, and fog |
| `sea_state_description` | ordered | Description of sea state, from "calm, glassy" to "very rough" |
| `longitude` | double | Decimal longitude |
| `latitude` | double | Decimal latitude (negative indicates Southern hemisphere) |

## Navigating the project

Our project is set-up as a scrollable website, where the Home page displays our final report, including an introduction, exploratory data analysis, modelling, discussion, and conclusion. The different sections are located in a *contents* section in the upper corner of the website. The Acknowledgments page includes our acknowledgements. Thank you for viewing our project!
