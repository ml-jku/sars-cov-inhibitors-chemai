# Large-scale ligand-based virtual screening for SARS-Cov-2 inhibitors using a deep neural network

Markus Hofmarcher, Andreas Mayr, Elisabeth Rumetshofer, Peter Ruch, Philipp Renz, Johannes Schimunek, Philipp Seidl, Andreu Vall, Michael Widrich, Sepp Hochreiter, Guenter Klambauer

ELLIS Unit @ LIT AI Lab & Institute for Machine Learning, Johannes Kepler University Linz, Austria

------------------------

Due to the current severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) pandemic, there is an urgent need for novel therapies and drugs. We conducted a large-scale virtual screening for small molecules that are potential CoV-2 inhibitors. To this end, we utilized *ChemAI*, a deep neural network trained on more than 220M data points across 3.6M molecules from three public drug-discovery databases. With ChemAI, **we screened and ranked one billion molecules from the ZINC database** for favourable effects against CoV-2. We then reduced the result to the 30,000 top-ranked compounds, which are readily accessible and purchasable via the ZINC database.

## Technical report:
[Technical report](SARS_cov_screen.pdf)

## Training data set for machine learning or other methods: 
[Data set](http://www.bioinf.jku.at/people/klambauer/sars_cov_dataset.zip)

## Predictions and ranking for DrugBank compounds:
Available on reasonable request for scientific purposes. Send request to: klambauer@ml.jku.at

## List of 30,000 ranked compounds from ZINC
The list is available in [csv format](sars-cov-library.csv) for automated processing and in [Excel format](sars-cov-library.xlsx) for manual inspection.

Here are some examples of the top-ranked molecules:

| | | | |
|:---:|:---:|:---:|:---:|
| ![ZINC000254565785](assets/ZINC000254565785.svg?sanitize=true) | ![ZINC000726422572](assets/ZINC000726422572.svg?sanitize=true) | ![ZINC000916265995](assets/ZINC000916265995.svg?sanitize=true) | ![ZINC000916356873](assets/ZINC000916356873.svg?sanitize=true) |
| [ZINC000254565785](https://zinc.docking.org/substances/ZINC000254565785/) | [ZINC000726422572](https://zinc.docking.org/substances/ZINC000726422572/) | [ZINC000916265995](https://zinc.docking.org/substances/ZINC000916265995/) | [ZINC000916356873](https://zinc.docking.org/substances/ZINC000916356873/) |
| ![ZINC000806591744](assets/ZINC000806591744.svg?sanitize=true) | ![ZINC000178971373](assets/ZINC000178971373.svg?sanitize=true) | ![ZINC000000155607](assets/ZINC000000155607.svg?sanitize=true) | ![ZINC000016317677](assets/ZINC000016317677.svg?sanitize=true) |
| [ZINC000806591744](https://zinc.docking.org/substances/ZINC000806591744/) | [ZINC000178971373](https://zinc.docking.org/substances/ZINC000178971373/) | [ZINC000000155607](https://zinc.docking.org/substances/ZINC000000155607/) | [ZINC000016317677](https://zinc.docking.org/substances/ZINC000016317677/) |
| ![ZINC000193073749](assets/ZINC000193073749.svg?sanitize=true) | ![ZINC000769846795](assets/ZINC000769846795.svg?sanitize=true) | ![ZINC000755523869](assets/ZINC000755523869.svg?sanitize=true) | ![ZINC000763345954](assets/ZINC000763345954.svg?sanitize=true) |
| [ZINC000193073749](https://zinc.docking.org/substances/ZINC000193073749/) | [ZINC000769846795](https://zinc.docking.org/substances/ZINC000769846795/) | [ZINC000755523869](https://zinc.docking.org/substances/ZINC000755523869/) | [ZINC000763345954](https://zinc.docking.org/substances/ZINC000763345954/) |
| ![ZINC000001448699](assets/ZINC000001448699.svg?sanitize=true) | ![ZINC000016940508](assets/ZINC000016940508.svg?sanitize=true) | ![ZINC000005486767](assets/ZINC000005486767.svg?sanitize=true) | ![ZINC000005527649](assets/ZINC000005527649.svg?sanitize=true) |
| [ZINC000001448699](https://zinc.docking.org/substances/ZINC000001448699/) | [ZINC000016940508](https://zinc.docking.org/substances/ZINC000016940508/) | [ZINC000005486767](https://zinc.docking.org/substances/ZINC000005486767/) | [ZINC000005527649](https://zinc.docking.org/substances/ZINC000005527649/) |
| ![ZINC000755497029](assets/ZINC000755497029.svg?sanitize=true) | ![ZINC000746495682](assets/ZINC000746495682.svg?sanitize=true) | ![ZINC000005719506](assets/ZINC000005719506.svg?sanitize=true) | ![ZINC000002149503](assets/ZINC000002149503.svg?sanitize=true) |
| [ZINC000755497029](https://zinc.docking.org/substances/ZINC000755497029/) | [ZINC000746495682](https://zinc.docking.org/substances/ZINC000746495682/) | [ZINC000005719506](https://zinc.docking.org/substances/ZINC000005719506/) | [ZINC000002149503](https://zinc.docking.org/substances/ZINC000002149503/) |
