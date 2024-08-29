# Overview
This code aims to quantify and analyse service accessibility (the first key metric: **A**) and the corresponding disparity between different popualtion groups (the second key metric: **fairness index**) by using demographical and mobile data (sample data provided for testing: [SampleData](/SampleData)). The two key metrics are first calculated (A: [GetKeyMetric_A](/GetKeyMetric_A.ipynb); fairness index: [GetKeyMetric_fairnessindex](/GetKeyMetric_fairnessindex.ipynb)), followed by the main analyses and visualization (see [MainAnalysesAndVisualization](/MainAnalysesAndVisualization)). All results in supplemental informain can be obtained by runing [AnalysesForSI](/AnalysesForSI.ipynb). This code is run using Python. 



# System requirements
## Hardware requirements
This code requires only a standard computer with enough RAM to support the in-memory operations.

## Software requirements
### OS requirements
This code has been tested on *Windows*.

### Python dependencies
This code mainly depends on the Python scientific and visualization packages：
```
pandas
numpy
geopandas
matplotlib
shapely
math
seaborn
plot_utils
ast
os
glob
statsmodels
```


# Installation guide
This code is written using *Jupyter Notebook* and has no additional installation requirements.

# Demo
- run [GetKeyMetric_A.ipynb](/GetKeyMetric_A.ipynb) using [sample data](/SampleData) to calculate the first key metric: **A**
* run [GetKeyMetric_fairnessindex.ipynb](/GetKeyMetric_fairnessindex.ipynb) to calculate the second key metric: **fairness index**
+ analyse these metrics and visualize the outcomes



