[![Build Status](https://travis-ci.org/mbbo/katalinter.svg?branch=master)](https://travis-ci.org/mbbo/katalinter)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./.github/PULL_REQUEST_TEMPLATE.md)

# Katalinter

The goal of this project is to use the librairie stylelint in a real HTML/CSS context and wrap it in a continuous integration environment.

 - [Getting Started](#gs)
 - [Prerequisites](#prerequisites)
 - [Installing](#installing)
 - [How to use it](#howToUseIt)

## <a name="gs"></a> Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### <a name="prerequisites"></a> Prerequisites

You need to have npm install on your system.

### <a name="installing"></a> Installing

To install the project, simply execute these commands.
```
git clone git@github.com:mbbo/katalinter.git
cd katalinter
npm i
```

### <a name="howToUseIt"></a> How to use it

To use this project you can break a rule describe in the stylintrc file and run this command.

```
npm run test
```

It should display an error.