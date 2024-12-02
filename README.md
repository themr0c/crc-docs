CRC User documentation; Getting Started Guide
=============================================

This repsoitory contains the user documentation, otherwise known as
"Getting Started Guide". The intention is to provide

  - a brief introduction
  - installation guide
  - basic usage guide


## Prerequisites
* A container engine, such as Podman or Docker.


## Build instruction
Build and serve the documentation using

```shell
$ make docs_serve
```

The documentation will be generated in `./public` and locally available at http://localhost:8088/.


## Devcontainer
Alternatively you can use a devcontainer. This will start the developer environment
inside an Antora container.

To make the documentation, you can run:

```bash
$ antora antora-playbook.yml
```

which will generate the output in `./public`.
