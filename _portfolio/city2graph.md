---
title: "city2graph: GeoAI with Graph Neural Networks"
excerpt: "A Python library for converting geospatial datasets into graph representations, providing an integrated interface for GeoPandas, NetworkX, and PyTorch Geometric. <br/><img src='https://raw.githubusercontent.com/c2g-dev/city2graph/main/docs/source/_static/social_preview.png'>"
collection: portfolio
---

## city2graph: GeoAI with Graph Neural Networks (GNNs) and Spatial Network Analysis

[![city2graph](http://city2graph.net/_static/social_preview.png)](http://city2graph.net)

**city2graph** is a Python library for converting geospatial datasets into graph representations, providing an integrated interface for [GeoPandas](https://geopandas.org/), [NetworkX](https://networkx.org/), and [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/) across multiple domains (e.g. streets, transportations, OD matrices, POI proximities, etc.).

### Key Features

[![scope](http://city2graph.net/_static/scope.png)](http://city2graph.net/_static/scope.png)

- **Graph Construction for GeoAI:** Build graphs from diverse urban datasets, including buildings, streets, and land use, to power GeoAI and GNN applications.
- **Transportation Network Modeling:** Analyze public transport systems (buses, trams, trains) by constructing detailed transportation graphs with support of GTFS format.
- **Proximity and Contiguity Analysis:** Create graphs based on spatial proximity and adjacency for applications in urban planning and environmental analysis.
- **Mobility Flow Analysis:** Model and analyze urban mobility patterns from various data sources like bike-sharing, migration, and pedestrian flows.
- **PyTorch Geometric Integration:** Seamlessly convert geospatial data into PyTorch tensors for GNNs.

### Project Information

- **Documentation:** [city2graph.net](https://city2graph.net)
- **GitHub Repository:** [github.com/c2g-dev/city2graph](https://github.com/c2g-dev/city2graph)
- **PyPI Package:** [pypi.org/project/city2graph](https://pypi.org/project/city2graph/)
- **Conda-forge:** [anaconda.org/conda-forge/city2graph](https://anaconda.org/conda-forge/city2graph/)

### Badges

[![PyPI version](https://badge.fury.io/py/city2graph.svg)](https://badge.fury.io/py/city2graph/) 
[![conda-forge Version](https://anaconda.org/conda-forge/city2graph/badges/version.svg)](https://anaconda.org/conda-forge/city2graph/) 
[![PyPI Downloads](https://static.pepy.tech/badge/city2graph)](https://pepy.tech/projects/city2graph) 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15858845.svg)](https://doi.org/10.5281/zenodo.15858845) 
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://github.com/c2g-dev/city2graph/blob/main/LICENSE)
[![codecov](https://codecov.io/gh/c2g-dev/city2graph/graph/badge.svg?token=2R449G75Z0)](https://codecov.io/gh/c2g-dev/city2graph)

### Installation

```bash
# Basic installation
pip install city2graph

# With PyTorch (CPU)
pip install "city2graph[cpu]"

# With PyTorch + CUDA (GPU)
pip install "city2graph[cu128]"
```

### Technologies Used

- Python
- PyTorch Geometric
- NetworkX
- GeoPandas
- OSMnx
- Shapely
