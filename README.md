# Canada Traffic Accident Severity Dashboard

Interactive dashboard on injury-collision severity in **Canada, Québec and Montréal**, and SVM models that predict severe (fatal or serious) outcomes.

**Live dashboard:** https://samikaradsheh.github.io/Canada-Traffic-Accident-Severity-Dashboard/

## What's inside

The whole dashboard is one file, `index.html`, with all data built in. Open it in any browser; it needs internet only to load the D3 chart library. It has six tabs:

| Tab | Shows |
|---|---|
| Overview | Headline numbers, severity by year, seasonality, Montréal outcomes, administrative regions, condition exposure |
| Conditions | Severity by lighting, weather, surface and speed; month × hour and speed × lighting heatmaps; collision types; road users; Montréal map |
| Canada comparison | Relative risk by weather and surface across Canada, Québec and Montréal; national odds ratios |
| Models | Model comparison, precision–recall curves, risk deciles, confusion matrices, imbalance strategies, sampling ratio, grid search, robustness checks |
| Regional models | Transfer test between regions, permutation importance, odds ratios by region |
| Data & method | Unified database summary, missing values, definitions and limitations |

## Data sources

* SAAQ, *Rapports d'accident* 2016–2022 (Données Québec)
* Ville de Montréal, *Collisions routières* 2012–2021 (Données Québec)
* Transport Canada, *National Collision Database* 2012–2020 (Open Government)

## Team

| Name | Student ID |
|---|---|
| Salma El Kanani | 40339588 |
| Mowafaq Ghali Kallas | 40084361 |
| Soulaimane Lahbabi | 40160918 |
| Sami Karadsheh | 40268817 |
| Tareq Haddadin | 40300116 |
| Ryan Draaoui | 40277027 |
