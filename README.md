# Vertex AI MLOps Workshop

This workshop provides a hands-on introduction to building and deploying machine learning models using Vertex AI MLOps.  You will learn how to create datasets, build pipelines, train models, and track experiments using various Vertex AI services.


## Prerequisites

* **Google Cloud Project:** You will need a Google Cloud Project with billing enabled.
* **Vertex AI API Enabled:** Ensure the Vertex AI API is enabled in your project.
* **Basic Python Knowledge:** Familiarity with Python programming is recommended.


## Workshop Outline

This workshop is divided into the following sections:

**1. Datasets:**  Learn how to work with datasets in BigQuery and Google Cloud Storage, and leverage Feature Store. ([01.dataset/datasets_bq_gcs.ipynb](01.dataset/datasets_bq_gcs.ipynb), [01.dataset/feature_store.ipynb](01.dataset/feature_store.ipynb))

**2. Pipelines:** Build and deploy machine learning pipelines using Vertex AI Pipelines. Explore AutoML and custom training pipelines. ([02.pipeline/automl_tabular_regression_pipeline.ipynb](02.pipeline/automl_tabular_regression_pipeline.ipynb), [02.pipeline/custom_tabular_regression_pipeline.ipynb](02.pipeline/custom_tabular_regression_pipeline.ipynb), [02.pipeline/kubeflow_pipeline_vertexai.ipynb](02.pipeline/kubeflow_pipeline_vertexai.ipynb))

**3. Training:** Train machine learning models using AutoML and custom training methods. ([03.training/automl_tabular_classification_petfinder.ipynb](03.training/automl_tabular_classification_petfinder.ipynb), [03.training/automl_tabular_regression_batch.ipynb](03.training/automl_tabular_regression_batch.ipynb), [03.training/automl_tabular_regression_online.ipynb](03.training/automl_tabular_regression_online.ipynb), [03.training/custom_training_classification-online.ipynb](03.training/custom_training_classification-online.ipynb))

**4. Experiments:** Track and compare experiments using Vertex AI Experiments. ([04.experiments/comparing_pipeline_experiments.ipynb](04.experiments/comparing_pipeline_experiments.ipynb), [04.experiments/tracking_metric_pipeline.ipynb](04.experiments/tracking_metric_pipeline.ipynb), [04.experiments/vertexai_experiments.ipynb](04.experiments/vertexai_experiments.ipynb))


## Conclusion

By the end of this workshop, you will have a solid understanding of how to build and deploy machine learning models on Vertex AI using MLOps principles. You will be able to leverage Vertex AI's powerful tools and services to streamline your ML workflows and improve model performance.
