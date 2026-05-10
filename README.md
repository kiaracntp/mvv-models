# MVV Cascade Modeling

Exploratory modeling notebooks for multivesicular vesicle (MVV) directed signaling cascades using BioCRNpyler to model CRNs and Bioscrape to simulate species concentration over time.

The main notebook compares bulk, one-compartment, two-compartment, and three-compartment MVV cascade models against experimental fluorescence data. It also includes sanity-check plots for intermediate species such as stachyose, glucose, H2O2, and resorufin.

## Notebook

- `notebooks/MVV_models_cleaned.ipynb`  
  Main exploratory modeling notebook containing model construction, model-vs-data comparisons, and sanity-check plots across increasing compartment complexity.

- `notebooks/3_Compartment_Tuning.ipynb`  
  Exploratory parameter-tuning notebook for testing how selected parameter changes affect the three-compartment model output. Some plots use interactive Bokeh outputs and may render best when opened locally in Jupyter or VS Code.

## Figures

Saved model/data and sanity-check plots are available in the `figures/` folder.

## Notes

This documents the exploratory computational modeling process. The notebooks show simulation outputs and biological interpretation of cascade behavior across increasing compartment complexity.
