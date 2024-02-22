# [Name Pixel App]

## Short Description

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla consectetur nisi vestibulum purus fermentum viverra. Nam turpis velit, tristique quis fermentum et, hendrerit non eros.

## Configuration

It is possible to install in your store either by using App Store or the VTEX IO Toolbelt.

## Using VTEX App Store

1. Access the **Apps** section in your account's admin page and look for the [NAME OF THE APP] box;
2. Then, click on the **Install** button;
3. Click on the pixel app configuration and activate the same;
4. You'll see a warning message in the console about needing to enter the necessary configurations. Scroll down and type in your **[APP NAME ID]**.
5. Click on **Save**.

## Using VTEX IO Toolbelt

1. ```install via VTEX CLI```

```bash

  vtex install electrolux.[app name]@0.x

```

2. Access the **Apps** section and follow the steps of the topic **Using Vtex App Store**

### Example

![Electrolux [Name] Pixel App Setup](./screenshots/admin-panel.png)

## Development

### Conventional Commits

This repository uses [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#specification) for better commit standardization.

The commit message should be structured as follows:

```text

<type>[optional scope]: <description>



[optional body]



[optional footer(s)]

```

Examples:

```text

feat: add new feature

chore(release): 1.0.0

```

Common types according to the [Angular convention](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines) can be:

- **build**: Changes that affect the build system or external dependencies (scope examples: gulp, broccoli, npm).

- **chore**: Other changes that don't modify source or test files.

- **ci**: Changes to CI configuration files and scripts (scope examples: Travis, Circle, BrowserStack, SauceLabs).

- **docs**: Documentation-only changes.

- **feat**: A new feature.

- **fix**: A bug fix.

- **perf**: A code change that improves performance.

- **refactor**: A code change that neither fixes a bug nor adds a feature.

- **revert**: Reverts a previous commit.

- **style**: Changes that do not affect the meaning of the code (white space, formatting, missing semicolons, etc.).

- **test**: Addition of missing tests or correction of existing tests.

### Commitizen

You can use the [Commitizen](https://commitizen-tools.github.io/commitizen) command-line interface to create Conventional Commits:

```bash

yarn commit

```

![Commitizen](https://raw.githubusercontent.com/commitizen/cz-cli/master/meta/screenshots/add-commit.png)

Please note that I have translated the text as is, but some context might be missing or specific to the original content. Make sure to adjust any URLs or other references as necessary.
