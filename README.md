geocoder for diffusion tube locations
=====================================
 
This is an important output from LTN-related comms - part of our narrative of monitoring - 'today we are launching a new map where you can see how much the AQ has improved in YOUR area' etc.

Current air quality objective (AQO) = 40 micrograms per cubic metre of air (μg m-3)) (assuming this is NO2 per cubic metre (μgm-3))

World Health Organization(WHO) Air Quality Guideline (AQG) levels = 10μg m-3 (revised in September 2021)

https://lewisham.gov.uk/myservices/environment/air-pollution/read-our-air-quality-action-plan-and-other-reports
 
https://lewisham.gov.uk/-/media/air-quality-analysis.ashx

https://lewisham.gov.uk/myservices/parking/schoolstreets/schools-streets-programme-streets-outside-schools

diffusion tubes 
---------------

![diffusion tube](./diffusion-tube.png)

[Diffusion tubes](https://lovecleanair.org/about-air-quality/how-pollutants-measured/diffusion-tubes/) are a cheap and easy way to measure nitrogen dioxide. They are supplied and analysed by laboratories. Councils use them to get an indication of air pollution levels across their borough by putting tubes in lots of different places. Residents and schools also use diffusion tubes for citizen science projects to measure their local air quality. Diffusion tube

Diffusion tubes are small plastic tubes with a cap at each end one of which is coloured. Under the coloured cap is a steel mesh disc which is coated with triethanolamine (TEA) a chemical that absorbs nitrogen dioxide. When gases pass over this mesh the chemical changes. This chemical change tells us how much nitrogen dioxide was in the air during the monitoring period.

Tubes are attached in a vertical position with the coloured cap at the top to a stationary object such as a lamppost, road sign, railings or a drainpipe. The bottom white cap is removed so that the air can get into the tube (known as diffusion). Nitrogen dioxide in the air reacts with the chemical on the mesh at the top of the tube and changes into nitrite. The tube must be left in place with the bottom cap off for 2-4 weeks, after which time the bottom cap is replaced and the tube is returned to the laboratory for analysis.

In the laboratory, the steel mesh is removed and washed with distilled water which is then analysed. The concentration of nitrogen dioxide is found by shining ultra violet light (UV) through the water sample. The amount of light absorbed is equivalent to the concentration of nitrogen dioxide that was present in the air during the monitoring period.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
