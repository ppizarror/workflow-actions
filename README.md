# workflow-actions

Workflow actions for continous integration development.

## Usage

Within workflow, use an action by providing its required parameters (if any):

```yml
uses: ppizarror/workflow-actions/.github/workflows/action.yml@master
strategy:
  matrix:
    os:
      - macos-latest
      - ubuntu-latest
      - windows-latest
    ...
with:
  os: ${{ matrix.os }}
  ...
```
