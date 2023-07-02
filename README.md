# CICD Workbench
Some materials and stuff about CICD using GitHub Actions workflows

## Workflows
* [mirror-yc-storage.yml](https://github.com/leitosama/cicd-workbench/blob/main/.github/workflows/mirror-yc-storage.yml) -- mirror given url to Yandex Cloud Object Storage. Run: `gh workflow run mirror-yc-storage.yml -f url="https://example.com"`

## Using with CLI
```bash
gh workflow list # list current workflows
gh workflow run <workflow-name> -f input=value # Run workflow with params (workflow_dispatch) only
```

