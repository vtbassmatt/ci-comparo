# ci-comparo
Running multiple hosted CIs in one project

## CI systems

| System | `master` badge | Config |
|--------|----------------|--------|
| [AppVeyor](https://ci.appveyor.com/project/vtbassmatt/ci-comparo/) | [![Build status](https://ci.appveyor.com/api/projects/status/5fjb9pketj8suqv4/branch/master?svg=true)](https://ci.appveyor.com/project/vtbassmatt/ci-comparo/branch/master) | [appveyor.yml](appveyor.yml) |
| [Azure Pipelines](https://dev.azure.com/vtbassmatt/ci-comparo/_build?definitionId=1) | [![Build Status](https://dev.azure.com/vtbassmatt/ci-comparo/_apis/build/status/vtbassmatt.ci-comparo?branchName=master)](https://dev.azure.com/vtbassmatt/ci-comparo/_build/latest?definitionId=1&branchName=master) | [azure-pipelines.yml](azure-pipelines.yml) |
| [CircleCI](https://circleci.com/gh/vtbassmatt/ci-comparo) | [![CircleCI](https://circleci.com/gh/vtbassmatt/ci-comparo.svg?style=svg)](https://circleci.com/gh/vtbassmatt/ci-comparo) | [.circleci/config.yml](.circleci/config.yml) |
| [Cirrus CI](https://cirrus-ci.com/github/vtbassmatt/ci-comparo) | [![Build Status](https://api.cirrus-ci.com/github/vtbassmatt/ci-comparo.svg)](https://cirrus-ci.com/github/vtbassmatt/ci-comparo) | [.cirrus.yml](.cirrus.yml) |
| [GitLab CI](https://gitlab.com/vtbassmatt/ci-comparo/pipelines) | [![pipeline status](https://gitlab.com/vtbassmatt/ci-comparo/badges/master/pipeline.svg)](https://gitlab.com/vtbassmatt/ci-comparo/commits/master) | [.gitlab-ci.yml](.gitlab-ci.yml) |
| [Travis CI](https://travis-ci.com/vtbassmatt/ci-comparo/) | [![Build Status](https://travis-ci.com/vtbassmatt/ci-comparo.svg?branch=master)](https://travis-ci.com/vtbassmatt/ci-comparo) | [.travis.yml](.travis.yml) |

If you want to add one, please do so in alphabetical order.

## Disclosure

I was a PM for Azure Pipelines.
This wasn't a marketing site or head-to-head competition between these systems.
It didn't exercise all the amazing capabilities that the different CI systems offer.
