# BA Data Paths

The data installed with Esri Business Analyst Desktop is a treasure trove for doing robust analysis. However, accessing this data though the Python environment is next to impossible. For my own convenience I have created this package to streamline when I need to access this data in my own projects and daily work. Please feel free to use it if it benefits your workflows as well.

## Installation

BA Data Paths can easily be installed as a pip package.

```python3
pip install ba-data-paths
```

## Basic Use - Getting Startedw

Almost everything is built around a single BA_Data object instance you can import called `ba_data`. The easiest way to get started is to import this from the module and access the properties and methods from there. For instance, to see a dataframe of the available enrichment variables in a Jupyter Notebook.

```python3
from ba_data_paths import ba_data

vars_df = ba_data.enrich_vars_dataframe

vars_df
```