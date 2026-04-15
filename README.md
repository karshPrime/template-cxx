
## Copier

This repository provides a [copier](https://copier.readthedocs.io/en/stable/)
template for creating C development environments. It offers a consistent and
reproducible setup across projects and makes it easy to apply improvements when
the template is updated.


### Prerequisites

Install the Copier command:
* **Quick option:** `uv tool install copier`
* **Documentation:** https://copier.readthedocs.io/en/stable


### Create New Project

Run the following command:

```bash
$ copier copy git@github.com:karshPrime/template-c path/to/project --trust
```
Answer the Copier prompts to configure the project.
* **Project Description:** Optional plain‑text description of the project.
* **Library Pack:** Optional selection of libraries to include in the project.

**Note:** The `--trust` option is required because the template runs `git`
commands.


## Project Features

* **Example application and module structure**: Includes a minimal command‑line
  entry point (main.c) and a simple module layout.

* **Allows for setting more specific starting point**: With library packs, a
  number of different templates are configured out of the box - setting generic
  minimum setup required for the usecase.

