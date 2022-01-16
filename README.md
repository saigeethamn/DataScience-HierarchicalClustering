# DataScience-HierarchicalClustering

Problem Statement
An international humanitarian NGO has got a $ 10 million fuding. The CEO needs to decide how to use this money effectively and strategically. The significant choice at hand is the countries that are in dire need of aid.

We need to be able to categorise countries using some socio-economic and health factors that determine the overall development of the country.This will help the CEO to understand where to focus the most.

## Preparatory Steps

The preparatory steps are as outlined in this blog:
 https://www.saigeetha.in/post/steps-towards-data-science-or-machine-learning-models
 
## Modeling
Having done the pre-requisite transformations and data preparation, the Hierarchical algorithm provided by scipy library is used and the clusters of countries are formed based on thier health and socio-economic factors. 

## Cluster Profiling
The Cluster Profiling finally shows that 3 clusters are pretty distinct with about 50 countries falling in the cluster that is in need of aid. Among them, three important factors of income, child mortality and gdpp are used to decide the top 10 countries that would benefit the maximum in getting aid. 

Since 50 is a large number of countries to give aid to, the hierarchical clustering is done with a cut-off at 5, implying 5 clusters are created. That separates the 50 countries into 38 highly needy countries and 12 who could come in the next lot.

Among these 38 countries, criteria is applied to get the top 5-10 countries that can be looked at in the first round of funding