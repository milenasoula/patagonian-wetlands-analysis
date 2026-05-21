# patagonian-wetlands-analysis

Environmental and multivariate analysis of Patagonian mountain wetlands using R.

## Abstract

Patagonian mountain wetlands are biodiversity-rich ecosystems exposed to increasing climatic and anthropogenic pressures. This project evaluates spatial and temporal patterns of aquatic macroinvertebrate communities across Andean and Subandean wetlands using physicochemical measurements, Generalized Linear Mixed Models (GLMM), and beta diversity analyses (LCBD). Results highlight strong elevation effects, nutrient-related biodiversity responses, and marked interannual variability associated with climatic conditions.

## Methods

Methods included:

- Environmental and ecological data analysis
- Statistical modeling in R
- Generalized Linear Mixed Models (GLMM)
- Beta diversity analysis (LCBD)

## Tools and packages

- R
- tidyverse
- glmmTMB
- DHARMa
- emmeans
- adespatial

## Repository structure

- `scripts/` → R scripts for data cleaning, statistical modeling, LCBD analysis, and figure generation
- `figures/analysis/` → study system map, statistical figures, and model visualizations
- `figures/fieldwork/` → field campaign, wetland ecosystem, sampling, and laboratory photography
- `results/` → summary tables and GLMM model outputs

## README structure

- `Abstract` → project context, objectives, analytical approach, and main ecological relevance
- `Methods` → summary of the statistical and ecological methods used
- `Study system` → geographic and ecological context of the sampled wetlands
- `Example figures` → selected visual outputs from the environmental and biodiversity analyses
- `Model outputs` → summarized environmental data and GLMM results
- `Key findings` → main patterns identified across elevation, nutrients, and years
- `Ecological interpretation and conservation relevance` → broader implications for monitoring, climate sensitivity, and conservation
- `Skills demonstrated` → technical, analytical, fieldwork, and laboratory skills shown by the project
- `Reproducibility` → basic instructions for reproducing the analytical workflow

## Study system

Mountain wetlands from Cordón Esquel, Patagonia, Argentina.

![](./figures/analysis/study_system_patagonia_wetlands.png)

*Location of Andean and Subandean wetlands sampled across the Esquel Mountain Range, Patagonia, Argentina.*

## Example figures

### Environmental predictors of macroinvertebrate richness

Generalized Linear Mixed Models (GLMM) revealed significant relationships between taxonomic richness, elevation, and nutrient concentrations across mountain wetlands.

![](./figures/analysis/richness_environmental_glmm.png)

---

### Spatial and temporal variability in macroinvertebrate abundance

Modeled abundance patterns across Andean and Subandean wetlands showed strong interannual variability and significant elevation × year interactions.

<p align="center">
  <img src="./figures/analysis/macroinvertebrate_abundance_temporal.png" width="75%">
</p>

---

### Local contribution to beta diversity (LCBD)

LCBD analyses highlighted spatial differences in community uniqueness between wetland types.

<p align="center">
  <img src="./figures/analysis/lcbd_elevation_model.png" width="45%">
</p>

## Model outputs

### Environmental summary statistics

Summary of physicochemical variables measured across Andean and Subandean wetlands during the 2018, 2024, and 2025 sampling campaigns.

![](results/environmental_summary_table.png)

---

### GLMM results — Block 1

Generalized Linear Mixed Models evaluating relationships between taxonomic richness, elevation, and nutrient concentrations.

![](results/glmm_block1_results.PNG)

---

### GLMM results — Block 2

Generalized Linear Mixed Models evaluating spatial and temporal variability in richness, abundance, and local contribution to beta diversity (LCBD).

![](results/glmm_block2_results.PNG)


## Key findings

- Mountain wetlands from the Esquel Mountain Range showed clear environmental differentiation along the altitudinal gradient.

- Subandean wetlands exhibited:
  - higher temperatures,
  - higher conductivity,
  - and increased nutrient concentrations.

- Andean wetlands were characterized by:
  - colder waters,
  - lower conductivity,
  - and oligotrophic conditions.

- Taxonomic richness was significantly associated with nutrient availability, particularly phosphate and nitrate/nitrite concentrations.

- Elevation influenced macroinvertebrate community structure, affecting:
  - richness,
  - abundance,
  - and Local Contribution to Beta Diversity (LCBD).

- Interannual climatic variability influenced community dynamics:
  - richness and abundance varied among years,
  - while LCBD remained comparatively stable.

- Results suggest that mountain wetlands are highly sensitive ecosystems where both local physicochemical conditions and large-scale climatic variability shape biological assemblages.

<p align="center">
  <img src="./figures/fieldwork/high_mountain_fieldwork.png" width="48%">
  <img src="./figures/fieldwork/andean_sampling_campaign.png" width="48%">
</p>
*High-elevation field campaigns and wetland sampling across Andean Patagonia.*

## Ecological interpretation and conservation relevance

Mountain wetlands from Patagonia function as environmentally heterogeneous and climatically sensitive ecosystems.

This study supports the use of aquatic macroinvertebrates as low-cost ecological indicators capable of detecting environmental variation across elevation and between climatic periods.

The observed interannual variability may be linked to broader climatic oscillations such as ENSO events, which influence regional precipitation dynamics in Patagonia.

These ecosystems are exposed to increasing anthropogenic pressures including:
- water extraction,
- livestock activity,
- off-road vehicle transit,
- tourism,
- and potential mining development.

Because mountain wetlands act as biodiversity reservoirs and freshwater regulation systems, long-term ecological monitoring is essential for conservation and management strategies under climate change scenarios.

<p align="center">
  <img src="./figures/fieldwork/andean_wetland_climate_sensitivity.png" width="48%">
  <img src="./figures/fieldwork/subandean_wetland_ecosystem.png" width="48%">
</p>
*Contrasting Andean and Subandean wetland ecosystems sampled during the study.*

## Skills demonstrated

- Ecological data analysis and statistical modeling in R
- Generalized Linear Mixed Models (GLMM)
- Multivariate ecological analysis
- Environmental data visualization and interpretation
- Long-term ecological monitoring
- Reproducible analytical workflows
- Scientific reporting and communication
- Field campaign planning and logistics coordination
- High-altitude wetland sampling in Patagonia
- Physicochemical and biological sample collection and processing
- Integration of field ecology, laboratory analyses, and quantitative data analysis

<p align="center">
  <img src="./figures/fieldwork/wetland_macroinvertebrate_sampling.png" width="48%">
  <img src="./figures/fieldwork/macroinvertebrate_samples.png" width="48%">
</p>
*Aquatic macroinvertebrate sampling and laboratory sample processing.*

<p align="center">
  <img src="./figures/fieldwork/case_building_caddisfly.png" width="35%">
</p>

*Case-building caddisfly larva collected from Patagonian mountain wetlands.*

---

## Reproducibility

Analyses were performed in R using reproducible workflows for data cleaning, statistical modeling, and visualization.

To reproduce the analyses:

1. Clone the repository
2. Open scripts in RStudio
3. Install required packages
4. Run scripts sequentially
