### About this course
In the first part of the course, you will learn to use the Azure Machine Learning Data Prep SDK with Azure Databricks to perform common data wrangling tasks and create optimized datasets for model development. In this workshop, we will use the Adventure Works retail data set to see how we can transform the dataset for building a content based recommender.

In the second half, we will also use Azure Machine Learning SDK do deploy a content based recommender to Azure Container Instance (ACI). As a follow up to this, we will then deploy it to Azure Kubernetes Service (AKS) for high-scale production scenarios.

Additionally, we have also included an optional lab to build a scalable recommeder using MovieLens dataset based on collaborative filtering with Azure Databricks.   

#### Step 1: Data Preparation

The goal of this session to get introduced to Azure Machine Learning Data Prep SDK. The learning objectives are:

1. Learn how to use Azure Machine Learning Data Prep SDK with Databricks
2. Read data from multiple sources (SQL DB, csv, Azure Data Lake, Excel, via mounts, etc.) and learn about Smart Read capability
3. Learn how to use Azure Machine Learning Data Prep SDK for performing data transformations such as Auto Joins, Fuzzy Groupings, Custom Transformations, etc.

#### Step 2: Deploy to ACI/AKS

In this session, we will learn about deploying a simple content based recommender. Specifically, the learning objectives are:
1. Learn how to build a simple content based recommender
2. Learn how to use Azure Machine Learning SDK with Databricks to perform deployment of the recommender to ACI and AKS
3. Learn how to use deep learning to build a content based recommender (optional)

#### Architecture
![Architecture](RSArchitecture.png)

#### Technologies Covered
![Technology](RSTechnologyMap.png)

#### Industry application

Recommendation systems have a wide range of industry applications. Here are some examples: 

Ecommerce/Retail Stores – Almost every ecommerce retail site uses some form of recommender system for product suggestions, brand recommendations and targeted ads relevant to user behavior and product/brand ratings.

Entertainment – Video streaming companies heavily use recommendation systems to make personalized suggestions to viewers based on the usage patterns and ratings on the shows. Audio streaming companies use recommendation systems suggest weekly selections that aim at improving listener retention and increase usage. 

Insurance, Internet Service Providers, and Mobile/wireless companies – Recommendation systems are used to provide customers with optimized and economical service plans based on customer usage patterns enhancing customer loyalty. 

#### Pre-requisites

1.	Experience with [Python](https://www.edx.org/course/introduction-python-data-science-2#!) coding

2.	Experience with [Jupyter notebooks](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)

3.	Be able to launch a [DataBricks workspace on Azure](https://docs.microsoft.com/en-us/azure/azure-databricks/quickstart-create-databricks-workspace-portal) and spin up clusters

#### Pre-setup before you attend this course:
1.	You need a Microsoft Azure account to create the services we use in our solution. You can create a [free account](https://azure.microsoft.com/en-us/free/), use your [MSDN account](https://azure.microsoft.com/en-us/pricing/member-offers/credit-for-visual-studio-subscribers/) or use any other subscription where you have permission to create services

#### Course Details

Primary Audience: Data Scientists, Azure AI Developers, Architects
Secondary Audience: Any professional interested in Microsoft Automated ML, Recommendation Engines

#### Level
This is designed as an advanced level course for Data Scientists/ AI Developers / Architects

#### Type
This course in its full form is designed to be taught in-class, but you can also use the materials in a self-paced fashion. There are assignments, and multiple reference links throughout the materials that support the concepts and skills you will learn.

#### Length
Full Course class room training:  8 hours

#### Course Modules
This course is organized in following modules
1. Introduction to recommendation systems ~ 30 min
2. Install and Configuration ~ 30 mins
3. Data Preparation with Azure ML DataPrep SDK and Azure Databricks ~ 3 hrs
4. Deploy Content based Recommender to ACI ~ 2 hrs
5. Deploy Content based Recommender to AKS ~ 1 hr
6. Discuss Learnings ~ 30 min

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
