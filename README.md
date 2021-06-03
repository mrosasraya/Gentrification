# Prediction of Transit-Induced Gentrification in Melbourne
## Table of Content

1. [Description](#desc)

2. [Main procedures](#main)

    2.1 [Notebook 1: ](#n1)

    2.2 [Notebook 2: ](#n2)

    2.3 [Notebook 3: ](#n3)

3. [Preprocessing](#prep)

    3.1. [Notebook 4: ](#n4)

    3.2. [Notebook 5: ](#n5)

    3.3. [Notebook 6: ](#n6)

    3.4. [Notebook 7: ](#n7)



## Description <a name='desc'></a>

This project attempts to model gentrification from a machine learning framework with a few key differences to what has been done previously published. Though there are some instances of using Random Forest and Neural Networks in the detection of gentrification, they have never been paired with a threshold-based definition of gentrification. By doing this, the classification task becomes independent from experts' input, possibly subjective interpretation of gentrification, and gentrification-like visual changes. Furthermore, the main contribution of this project is the addition of topological properties of public transport networks and results' analysis to prove transit-induced gentrification.

The inspiration for this project originated from the number of transit-oriented projects planned to take place in Melbourne and the alarming crisis of affordable housing in Australia. Concretely, the Suburban Rail Loop proposes a change in the use and structure of the rail system in Melbourne that could change the social landscape of areas currently poorly serviced by public transport.

This project is created to inform multidisciplinary teams of professionals. It is of the utmost importance to guide the decision-making for the improvement of the quality of life of vulnerable groups and the protection of communities. Many strategies should be taken seriously by stakeholders when developing infrastructure for transit projects such as the construction of social housing, the development of amenities for current inhabitants and not gentrifiers, tax-collection and control of property values, and more.

The method here presented revolves around the feature engineering of topological properties in the rail network and the tram network. The results show that these features are informative to the classification task of gentrification "prediction". In particular, degree centrality in the train system appears to be crucial for the calculation of places at risk of gentrification. This topological property is a distinctive characteristic in the design of the Suburban Rail Loop. 
The contents of this research are in the process of being peer-reviewed. Here is the abstract:

&nbsp; *The most common approaches in existing quantitative studies of gentrification use lin- ear models when working with structured socio-demographic data. This report seeks to elevate the predicting power of modeling gentrification as a supervised-learning clas- sification task under the framework of machine learning applied to the study case of Melbourne. The present study focuses on transit-induced gentrification by integrating topological properties of Melbourne’s public transport systems: tram and train. Said approach allows the research here undertaken to sustain the following claims. Firstly, feed-forward neural networks outperform linear approaches. Secondly, topological fea- tures are informative to the detection of areas at risk of gentrification. Consequently, degree centrality rises as the most meaningful topological feature centering attention on the areas surrounding transfer stations in the train system. Third, the evidence around the construction of 2 train stations suggests that transit-oriented developments can in- duce gentrification upon adjacent areas. Lastly, as a byproduct of using machine learning to model transit-induced gentrification in Melbourne, one can obtain a collection of most meaningful socio-demographic features that constitute the unique fingerprint of stages before gentrification in the city.*

The preprocessing of data makes use the following libraries:
Geopandas: https://geopandas.org
Tobler: https://pysal.org/tobler/
networkx: https://networkx.org


## Main Procedures <a name='main'></a>

### Notebook 1:  <a name='n1'></a>
### Notebook 2:  <a name='n2'></a>
### Notebook 3:  <a name='n3'></a>

## Data Pre-Processing <a name='prep'></a>

### Notebook 4:  <a name='n4'></a>
### Notebook 5:  <a name='n5'></a>
### Notebook 6:  <a name='n6'></a>
### Notebook 7:  <a name='n7'></a>

