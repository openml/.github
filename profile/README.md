### 🙋‍♀️ Who are we?
OpenML aims to democratize machine learning by creating an open, frictionless platform for accessing and sharing datasets, models, and experiments. Anytime, anywhere. It allows scientists to easily build on each other's work, learn from the past, and automate their workflows. [Check our website to learn more](https://new.openml.org/).

### 🌈 Contribution guidelines
If you are new to OpenML, please see our [general contribution guide](https://new.openml.org/contribute#help). We're so happy that you want to help!
We are open to anyone getting involved, and are always seeking to increase diversity in AI.

⚠️ At the moment, we're doing some significant rewriting of several components:
* [openml.org](https://github.com/openml/openml.org) (website): The new website (in /app) is being refactored until 25/12/2025, expect major changes. If you'd like to contribute to the website, you are very welcome but please check back on 1 January 2026.
* [OpenML](https://github.com/openml/OpenML) (backend): We are entirely rewriting the REST API from PHP to Python (early work can be found in [API v2](https://github.com/openml/server-api)). Pull requests to the old REST API may no longer be accepted. Please check back in spring 2026.

We do very much welcome contributions to other OpenML components, especially [Python API](https://github.com/openml/openml-python) and [documentation](https://github.com/openml/docs).

### 🍿 Get in touch
You can talk to us in [our Slack channel](https://join.slack.com/t/openml/shared_invite/enQtODg4NjgzNTE4NjU3LTYwZDFhNzQ5NmE0NjIyNmM3NDMyMjFkZDQ0YWZkYWYxMTIxODFmMDhhMTUzMGYzMmM4NjIzYTZlYjBkOGE5MTQ).
Or, join us in one of our [meetups](https://new.openml.org/meet).

### 👩‍💻 GitHub repository structure
Here's a brief overview of the repo's in OpenML and their status:

* [openml.org](https://github.com/openml/openml.org): Our [new frontend](https://new.openml.org/). Built on Flask, React, and Dash
* [OpenML](https://github.com/openml/OpenML): Our older backend, with a lot of legacy code. A complete rewrite is in the works (see apiv2)
* [API v2](https://github.com/openml/server-api): The new backend, under active development (not released yet).
* [openml-python](https://github.com/openml/openml-python): Our Python API, giving you access to everything OpenML has to offer
* [openml-R](https://github.com/openml/openml-R): Our R API, covering the major OpenML use cases
* [openml-java](https://github.com/openml/openml-java): Our Java API, covering the major OpenML use cases
* [openml-tensorflow](https://github.com/openml/openml-tensorflow): Our TensorFlow integration, work in progress
* [openml-pytorch](https://github.com/openml/openml-pytorch): Our PyTorch integration, work in progress
* [docs](https://github.com/openml/docs): Home of our [documentation pages](https://docs.openml.org/)
* [blog](https://github.com/openml/blog): Home of our [blog](http://blog.openml.org/)
* [benchmark-suites](https://github.com/openml/benchmark-suites): Materials to help you build [OpenML benchmark suites](https://docs.openml.org/benchmark/)
* [automlbenchmark](https://github.com/openml/automlbenchmark): Our framework for [benchmarking AutoML systems](https://openml.github.io/automlbenchmark/)








