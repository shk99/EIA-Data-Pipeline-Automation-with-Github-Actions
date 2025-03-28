# Data Pipeline Automation with GitHub Actions

## Instructions

Fork this repo to follow along with the course. The course has tracks for R and Python users, and you can choose to follow one or both. The R code examples are available under the [R folder](https://github.com/RamiKrispin/data-pipeline-automation-with-github-actions-4503382/tree/main/R); likewise, the Python code examples are available under the [python folder](https://github.com/RamiKrispin/data-pipeline-automation-with-github-actions-4503382/tree/main/python).

This repo has VScode [setting](https://github.com/RamiKrispin/data-pipeline-automation-with-github-actions-4503382/blob/main/.devcontainer/devcontainer.json) to launch the repo inside a Docker container using the Dev Containers extension. The course image was built to support amd64 CPU architecture in line with the GitHub Actions container support. Alternatively, you can install locally the required R or Python requirements using the [required_packages.R](https://github.com/RamiKrispin/data-pipeline-automation-with-github-actions-4503382/blob/main/R/required_packages.R) for R and [requirements.txt](https://github.com/RamiKrispin/data-pipeline-automation-with-github-actions-4503382/blob/main/.devcontainer/requirements.txt) for Python.


Throughout the course, we will work with the EIA API to pull data and metadata. The EIA API is open and free, and an API key is required to access it. To register to the API and set your key, go to the [EIA website](https://www.eia.gov/opendata/index.php) and follow the registration instructions.


For learning purposes, we store the data pipeline outputs and metadata locally, in the [csv](https://github.com/RamiKrispin/data-pipeline-automation-with-github-actions-4503382/tree/main/csv) and [metadata](https://github.com/RamiKrispin/data-pipeline-automation-with-github-actions-4503382/tree/main/metadata) folders.

