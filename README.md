# asteroid-classification-catboost
Simple implementation of CatBoost used for asteroid classification

## Dataset
This code use dataset from Kaggle NASA Asteroid Classification https://www.kaggle.com/shrutimehta/nasa-asteroids-classification

### Content
The data is about Asteroids - NeoWs. NeoWs (Near Earth Object Web Service) is a RESTful web service for near earth Asteroid information. With NeoWs a user can: search for Asteroids based on their closest approach date to Earth, lookup a specific Asteroid with its NASA JPL small body id, as well as browse the overall data-set.

### Acknowledgements
All the data is from the (http://neo.jpl.nasa.gov/). This API is maintained by SpaceRocks Team: David Greenfield, Arezu Sarvestani, Jason English and Peter Baunach.

## Methods
Classifier used is CatBoost developed Yandex (https://github.com/catboost/catboost). CatBoost is a machine learning algorithm that uses gradient boosting on decision trees. It is available as an open source library. We also use XGBoost as a comparison (https://xgboost.readthedocs.io/en/latest/)

## References
N. Anthony and M. R. Emami, “Asteroid engineering: The state-of- the-art of near-earth asteroids science and technology,” Progress in Aerospace Sciences, vol. 100, pp. 1–17, 2018. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S0376042118300277

E. A. Smirnov and A. B. Markov, “Identification of asteroids trapped inside three-body mean motion resonances: a machine-learning approach,” Monthly Notices of the Royal Astronomical Society, vol. 469, no. 2, pp. 2024–2031, 04 2017. [Online]. Available: https://doi.org/10.1093/mnras/stx999

A. Si, “Hazardous asteroid classification through various machine learning techniques,” International Research Journal of Engineering and Technology, vol. 07. [Online]. Available: issue:03 https://www.irjet.net/archives/V7/i3/IRJET-V7I31084.pdf
