# Setup a working xy compiler and tools

A GitHub action that installs and configures the latest version of [xyc](https://xy-lang.org).

## Example

```yaml
jobs:
    build_project:
        name: Build Project 
        runs-on: ubuntu-latest
        steps:
            - name: Install xyc
              uses: xy-org/setup-xy
            - run: xyc myproject
```
