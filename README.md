# AML-HoL-CERN
Customized for CERN


# Azure Machine Learning Hands on Labs
Azure Machine Learning Hands on Lab created by Azure Readiness


This content is designed for audience without any prior Machine learning knowledge. It starts from very basics and goes to advanced topics. We will try to keep this content live and include more and more advanced lab sessions with real life scenarious. Thanks for your support and feedback to make this content better. 

### **Suggested timeline for Azure Machine Learning Hands On Lab (HOL)**

| Time (min)     | Activity |
| ---------------| ---------|
| 90             | [Introduction to Machine Learning.](https://github.com/kayapperson/AzureMLHoL-CERN/blob/master/intro-AzureML-Webinar-KayApperson.pdf) This is 07/20 session with end-to-end demos. |
| 20             | Lab1/prereq - [Setting up development environment.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/001-lab-setup.md) Steps 1.4-1.6 can be skipped.|
| 45             | Lab2/prereq - [Introduction to R, Python & Data Synthesis.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/002-lab-data-synth.md) One option is needed. Options A, D, and/or E are recommended.|
| 45             | Lab3 - [AzureML Experiments & Data Interaction.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/003-lab-data-interact.md) [Option A is recommended.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/003-lab-data-interact.md#331-option-a-access-data-use-existing-dataset)|
| 60             | Lab4 - [Develop and Consume AzureML Models.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/004-lab-azureml-experiment.md) |
| 45 optional    | Lab5 - [Custom Scripts (R & Python) in AML.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/005-lab-custom-script-r-python.md) To practice on your own. |
| 60             | Lab6 - [Evaluate model performance in AML.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/006-lab-model-evaluation.md) |
| 60 optional    | Lab7 - [Azure ML Batch Score, Retrain, Production and Automatization.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/007-lab-production-ops.md) |
| 45 optional    | Lab8 - [Recommendation System.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/008-lab-recommendation-system.md) To practice on your own, and this could be relevant.|
| 45 optional    | Lab9 - [Monetizing Azure ML Solution.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/009-lab-monetization.md) To practice on your own.|
| 90 optional    | Lab10 - [Case Study: Optical character recognition.](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/010-lab-cs-ocr.md) To practice on your own.|

### **Detailed contents of the HOL**

 - [Introduction to Machine Learning](https://github.com/kayapperson/AzureMLHoL-CERN/blob/master/intro-AzureML-Webinar-KayApperson.pdf)
    
1. [Setting up development environment](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/001-lab-setup.md)  
    * Overview
        * Objectives
        * Requirements
    * Create free tier Azure ML account  
    * Create standard tier Azure ML account  
    * Install R and R Studio  
    * Install Anaconda Python  

2. [Introduction to R, Python & Data Synth](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/002-lab-data-synth.md)  
    * Overview
        * Objectives
        * Requirements
    * Generate Synthetic Data
        * Microsoft Excel
        * R
        * Python
        * Microsoft Azure SQL Server
        * Microsoft Azure Blob Storage 
    * Other Dataset sources. Note: Use https://kayazureml.blob.core.windows.net/aml-hol/forestfires.csv instead of the link in the documentation, http://www.dsi.uminho.pt/~pcortez/forestfires/forestfires.csv. 

3. [AzureML Experiments & Data Interaction](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/003-lab-data-interact.md)  
    * Overview
        * Objectives
        * Requirements
    * Creating AzureML Experiment
    * Accessing Data
        * Access data, use existing dataset
        * Upload your own dataset
        * Upload your own compressed dataset
        * Manually enter data
        * Access data on Azure Storage
        * Access data on Azure SQL Database
        * Get data from an HTTP web request

4. [Develop and Consume AzureML Models](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/004-lab-azureml-experiment.md)
    * Overview
        * Objectives
        * Requirements
    * Working with AzureML Models
        * Training a model
        * Publishing a trained model as Web Service
        * Removing Web Service Redundant input & output parameters
        * Consume the ML Web Service in a C# application
        * Input data type

5. [Custom Scripts (R & Python) in AML](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/005-lab-custom-script-r-python.md)
    * Overview
        * Objectives
        * Requirements
    * R & Python Script Modules
        * Using Execute R Script module
        * Using Python Script module
        * R & Python compatibility with Azure ML

6. [Evaluate model performance in AML](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/006-lab-model-evaluation.md)
    * Overview
        * Objectives
        * Requirements
    * Performance evaluation
        * Splitting data
        * Scoring the model
        * Evaluate a Regression model
        * Evaluate more than one model
        * Cross Validation
    * Performance evaluation (cont.)
        * Evaluate a Binary classification model
        * Comparing two binary classification model
        * Cross Validation on Binary Classification
        * Evaluating a Multi-class classification model
    * Feature engineering
        * Which feature is or is not important?
        * Simpler method to measure a feature’s importance

7. [Azure ML Batch Score, Retrain, Production and Automatization](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/007-lab-production-ops.md)
    * Overview
        * Objectives
        * Requirements
    * Importance of Retraining, seeing the whole picture
    * Batch and Request/Response scoring web services
        * Stages to create a scoring web service
            * Request/Response Service (RRS)
            * Batch Execution Service (BES)
            * Web Service Input/Output Parameter alternatives
    * Azure ML Retraining

8. [Recommendation System](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/008-lab-recommendation-system.md)
    * Overview
        * Objectives
        * Requirements
    * Generate synthetic data
    * Recommend items to users
    * Find related users
    * Find related items
    * What to recommend for a brand new user?
9. [Monetizing Azure ML Solution](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/009-lab-monetization.md)
    * Overview
        * Objectives
        * Requirements
    * Azure ML Web Service Details
    * Create Azure Management API Service
    * CORS issue with Azure Machine Learnin Web Services
    * Restrict or Rate limit your Web Service
    * Test and Publish your Web Service

10. [Case Study: Optical character recognition](https://github.com/Azure-Readiness/hol-azure-machine-learning/blob/master/010-lab-cs-ocr.md)
    * Overview
        * Objectives
        * Requirements
    * Exploring and Understanding the Dataset
        * Process MINST database in Azure ML with Python script
        * Generate image tiles
    * Azure ML solution for OCR
        * Develope Azure ML experiment
        * Deploy as webservice
        * Parameters needed to publish with management API
    * Consuming the ML solution
        * Security of the API
    * Develop web application
        * Publish as Azure Web Application
    * Test the solution
    * Refine Features, Feature Engineering
