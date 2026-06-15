**Création d'une couche sémantique et visualisation Power BI

Présentation du projet**

Ce projet a pour objectif la conception d'une solution décisionnelle complète basée sur les données AdventureWorks. Il couvre l'ensemble de la chaîne analytique, depuis le Data Warehouse jusqu'à la visualisation des indicateurs métier dans Power BI.

L'objectif principal est de transformer les données transactionnelles en informations exploitables permettant aux décideurs d'analyser les performances commerciales, la rentabilité, les territoires de vente, les produits et l'efficacité des promotions.

**Architecture de la solution
# Contexte métier**

AdventureWorks est une entreprise spécialisée dans la vente d'équipements et accessoires liés au cyclisme.

La direction souhaite disposer d'une solution décisionnelle lui permettant de suivre les performances commerciales et financières de l'activité Internet.

Les données transactionnelles étant dispersées et peu adaptées à l'analyse, une couche sémantique a été développée afin de centraliser les indicateurs métier et de simplifier leur exploitation.

Cette solution permet aux décideurs :

* d'analyser l'évolution des ventes dans le temps ;
* d'identifier les catégories de produits les plus performantes ;
* d'évaluer la rentabilité des ventes ;
* de comparer les performances des territoires commerciaux ;
* de mesurer l'efficacité des campagnes promotionnelles ;
* de suivre les principaux indicateurs financiers à travers des tableaux de bord interactifs.

Le projet illustre la mise en œuvre complète d'une architecture décisionnelle moderne reposant sur SQL Server, SSAS Tabular et Power BI.


**Source de données AdventureWorksDW**

→ Data Warehouse SQL Server

→ Couche sémantique SSAS Tabular

→ Visualisation Power BI

**Technologies utilisées**

Microsoft SQL Server

SQL Server Analysis Services (SSAS Tabular)

DAX (Data Analysis Expressions)

Power BI Desktop

Power BI Service

GitHub

**Modèle dimensionnel**

Table de faits

FactInternetSales

Dimensions

DimDate

DimCustomer

DimProduct

DimProductSubcategory

DimProductCategory

DimGeography

DimSalesTerritory

DimPromotion

DimCurrency

**Objectifs métier**

Cette solution permet de répondre aux questions suivantes :

Comment évoluent les ventes au fil du temps ?

Quels produits génèrent le plus de revenus ?

Quels produits sont les plus rentables ?

Quels territoires performent le mieux ?

Quel est l'impact des promotions sur les ventes ?

Comment évoluent les marges et les coûts ?

**Résultats**

Le projet fournit une couche sémantique centralisée permettant la création de rapports interactifs et l'analyse des indicateurs de performance commerciaux à différents niveaux de granularité.

**Mesures métier**
| Mesure              | Description        |
| ------------------- | ------------------ |
| Ventes              | Chiffre d'affaires |
| Profit Net          | Bénéfice net       |
| Nombre de commandes | Volume de ventes   |
| Marge %             | Rentabilité        |
| Cost Ratio          | Ratio des coûts    |

**## Fonctionnalités analytiques**

- Analyse des ventes dans le temps
- Analyse de la rentabilité
- Analyse des catégories de produits
- Analyse des territoires de vente
- Analyse des promotions
- Suivi des KPI commerciaux


