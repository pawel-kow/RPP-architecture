# RPP Architecture
This repository contains the initial draft of the RPP (RESTful Provisioning Protocol) architecture. 

## Overview
The [Architecture](https://pawel-kow.github.io/RPP-architecture) file outlines the core components, design considerations, and requirements for RPP. 

Key sections include:
* **Introduction:** Background on EPP and the motivation for RPP.
* **Terminology:** Definitions of key terms used in the document.
* **Requirements:** Essential and desirable features of RPP.
* **Architectural Overview:** General considerations about RPP architecture
* **Protocol Details:** More detailed description of the architecture layers and their components.

## Generating IETF I-D
`draft-kowalik-rpp-architecture-*.adoc` file is the source file to generate I-D.

In order to generate I-D documents the following script [generate.sh](./generate.sh) is provided.

Required tools:
- xml2rfc
- metanorma

The [.devcontainer](./.devcontainer) folder contains configuration for [VSCode Dev Container extension](https://code.visualstudio.com/docs/devcontainers/containers) with corresponding [Dockerfile](./.devcontainer/Dockerfile) including all necessary tools.

## Contributing
This draft is open for contributions and comments. We welcome feedback and suggestions to improve the architecture. To contribute, please submit a pull request or open an issue in this repository.
