# Integrating CI/CD for Kasuwa.

We are a team of five currently building a minimum viable product for a phone store, the stack we're using is flask (Python), Now as the team lead i have to setup the project guidelines in order to have a unified codebase. Here's How i'd implement Continuous Integration.

First i'd start with linting to analyze code for errors and to setup a specific code style. For this i'd be using Pylint since it offers in-depth analysis and can detect a wider range of potential issues and can also handle the configuration to align with the project style.

For testing i'd pick Pytest since its quite popular and versatile and also well suited for unit, integration and functional test.

Building. Flask doesn't require a build step, but i'd want to package the application using setuptools. used to define project metadata and source distribution.

## Alternatives To Setup CI
There are tools like CircleCi, Gitlab CI/CD, Travis CI and a lot more.

## Project Setup Environment
Since its not a large project and we're a small team i'd pick the cloud based option based on lower costs and predictable pricing, easy maintenance to enable the team focus on building, flexibility and faster setup that way we are more organised and focused on our individual roles to deliver the product and maintain the project easily for future needs. 
