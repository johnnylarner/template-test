# My Project

A short summary of the project

## Getting Started

To set up your local development environment, please use a fresh virtual environment with:

    conda env create --name my-project --file=environment-dev.yml

Then activate the environment with:

    conda activate my-project

To update this environment with your production dependencies, please run:

    conda env update --file=environment.yml

You can now import functions and classes from the module with `import my_project`.

### Testing

We use `pytest` as test framework. To execute the tests, please run

    python setup.py test

To run the tests with coverage information, please use

    python setup.py testcov

and have a look at the `htmlcov` folder, after the tests are done.

### Distribution Package

To build a distribution package (wheel), please use

    python setup.py dist

this will clean up the build folder and then run the `bdist_wheel` command.

### Contributions

Before contributing, please set up the pre-commit hooks to reduce errors and ensure consistency

    pip install -U pre-commit
    pre-commit install

If you run into any issues, you can remove the hooks again with `pre-commit uninstall`.

## Contact

Jane Doe (contact@alexanderthamm.com)

## License

© Jane Doe
