# Workshop: Accelerate Your Development and CI/CD Pipelines with Dagger

- Event: [KCD Czech & Slovak 2025](https://kcd.live)
- Date: 2025-06-05
- [Slides](https://slides.sagikazarmark.com/2025-06-05-accelerate-your-development-and-cicd-pipelines-with-dagger)

## Prerequisites

-  Make sure Docker is installed and running.
-  Make sure [Go](https://go.dev/dl/) is installed.
-  Install the latest [Dagger CLI](https://docs.dagger.io/install).
-  Make sure you have a [GitHub](https://github.com) account set up with SSH keys.
-  Last, but not least: you'll need your favorite text editor or IDE.

## Usage

```shell
❯ just --list
Available recipes:
    build # build the application
    check # run both tests and linters
    fmt   # format code
    lint  # run linter
    run   # run the application
    test  # run tests
```
