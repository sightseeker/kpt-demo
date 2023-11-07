# kpt-demo

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] kpt-demo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree kpt-demo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init kpt-demo
kpt live apply kpt-demo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
