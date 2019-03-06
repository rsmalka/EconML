[![Build Status](https://dev.azure.com/ms/EconML/_apis/build/status/Microsoft.EconML?branchName=master)](https://dev.azure.com/ms/EconML/_build/latest?definitionId=49&branchName=master)

# Introduction 

The [ALICE project](https://www.microsoft.com/en-us/research/project/alice/) at Microsoft Research is 
aimed at applying Artificial Intelligence concepts to economic decision making.  The Microsoft EconML 
pacakge is part of that project, providing a toolkit that combines state-of-the-art machine learning 
techniques with econometrics in order to bring automation to complex causal inference problems.  This 
toolkit is designed to measure the causal effect of some treatment variable(s) `t` on an outcome 
variable `y`, controlling for a set of features `x`.  For more information about how to use this package, 
consult the documentation at https://econml.azurewebsites.net/.

# Getting Started

For developers, you can get starting by cloning this repository.  We use 
[setuptools](https://setuptools.readthedocs.io/en/latest/index.html) for building and distributing our package.
We rely on some recent features of setuptools, so make sure to upgrade to a recent version with
`pip install setuptools --upgrade`.  Then from your local copy of the repository you can run `python setup.py develop` to get started.

# Running the tests

This project uses [pytest](https:docs.pytest.org/) for testing.  To run tests locally after installing the package, 
you can use `python setup.py pytest`.

# Generating the documentation

This project's documentation is generated via [Sphinx](https://www.sphinx-doc.org/en/master/index.html).  To generate a local copy
of the documentation from a clone of this repository, just run `python setup.py build_sphinx`, which will build the documentation and place it
under the `build/sphinx/html` path.

The reStructuredText files that make up the documentation are stored in the [docs directory](docs/); module documentation is automatically generated by the Sphinx build process.

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