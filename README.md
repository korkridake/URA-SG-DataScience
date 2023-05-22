# URA Data Science: Visualizing Property Trends in Singapore

Analyse and Visualize Home Buying and Home Rental for Different Areas in SG 🇸🇬

## Tools used in this project

* [Poetry](https://python-poetry.org/): Dependency management - [article](https://towardsdatascience.com/how-to-effortlessly-publish-your-python-package-to-pypi-using-poetry-44b305362f9f)
* [Prefect](https://www.prefect.io/): Orchestrate and observe your data pipeline - [article](https://medium.com/the-prefect-blog/orchestrate-your-data-science-project-with-prefect-2-0-4118418fd7ce?sk=552f3e60344175768dabbbf033776ce7)
* [Pydantic](https://docs.pydantic.dev/): Data validation using Python type annotations - [article](https://towardsdatascience.com/build-a-full-stack-ml-application-with-pydantic-and-prefect-915f00fe0c62?sk=b1f8c5cb53a6a9d7f48d66fa778e9cf0)
* [pre-commit plugins](https://pre-commit.com/): Automate code reviewing formatting  - [article](https://towardsdatascience.com/4-pre-commit-plugins-to-automate-code-reviewing-and-formatting-in-python-c80c6d2e9f5?sk=2388804fb174d667ee5b680be22b8b1f)
* Makefile: Create short and readable commands for repeatable tasks - [article](https://the-turing-way.netlify.app/reproducible-research/make/make-examples.html)
* [GitHub Actions](https://docs.github.com/en/actions): Automate your workflows, making it faster to build, test, and deploy your code - [article](https://pub.towardsai.net/github-actions-in-mlops-automatically-check-and-deploy-your-ml-model-9a281d7f3c84?sk=d258c20a7ff7a1db44327c27d3f36efb)
* [pdoc](https://github.com/pdoc3/pdoc): Automatically create an API documentation for your project

## Project structure
```bash
.
├── data            
│   ├── final                       # data after training the model
│   ├── processed                   # data after processing
│   ├── raw                         # raw data
├── docs                            # documentation for your project
├── .flake8                         # configuration for flake8 - a Python formatter tool
├── .gitignore                      # ignore files that cannot commit to Git
├── Makefile                        # store useful commands to set up the environment
├── models                          # store models
├── notebooks                       # store notebooks
├── .pre-commit-config.yaml         # configurations for pre-commit
├── pyproject.toml                  # dependencies for poetry
├── README.md                       # describe your project
├── src                             # store source code
│   ├── __init__.py                 # make src a Python module
│   ├── config.py                   # store configs 
│   ├── process.py                  # process data before training model
│   ├── run_notebook.py             # run notebook
│   └── train_model.py              # train model
└── tests                           # store tests
    ├── __init__.py                 # make tests a Python module 
    ├── test_process.py             # test functions for process.py
    └── test_train_model.py         # test functions for train_model.py
```

## Resources

* [chengguan/ura_api](https://github.com/chengguan/ura_api)
* [khuyentran1401/data-science-template: Template for a data science project](https://github.com/khuyentran1401/data-science-template)
* [Introduction – API Reference](https://www.ura.gov.sg/maps/api/)