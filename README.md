# winzy-convert

[![PyPI](https://img.shields.io/pypi/v/winzy-convert.svg)](https://pypi.org/project/winzy-convert/)
[![Changelog](https://img.shields.io/github/v/release/sukhbinder/winzy-convert?include_prereleases&label=changelog)](https://github.com/sukhbinder/winzy-convert/releases)
[![Tests](https://github.com/sukhbinder/winzy-convert/workflows/Test/badge.svg)](https://github.com/sukhbinder/winzy-convert/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/sukhbinder/winzy-convert/blob/main/LICENSE)

Mimic's convert to convert images to pdf, ppt etc.

## Installation

First [install winzy](https://github.com/sukhbinder/winzy) by typing

```bash
pip install winzy
```

Then install this plugin in the same environment as your Winzy application.
```bash
winzy install winzy-convert
```
## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:
```bash
cd winzy-convert
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
