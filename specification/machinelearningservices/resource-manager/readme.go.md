## Go

These settings apply only when `--go` is specified on the command line.

```yaml $(go) && !$(track2)
go:
  license-header: MICROSOFT_MIT_NO_VERSION
  clear-output-folder: true
  namespace: machinelearningservices
```

``` yaml $(go) && $(track2)
license-header: MICROSOFT_MIT_NO_VERSION
module-name: sdk/resourcemanager/machinelearningservices/armmachinelearningservices
module: github.com/Azure/azure-sdk-for-go/$(module-name)
output-folder: $(go-sdk-folder)/$(module-name)
azure-arm: true
```

### Go multi-api

```yaml $(go) && $(multiapi)
batch:
  - tag: package-2022-05-01
  - tag: package-2022-02-01-preview
  - tag: package-2022-01-01-preview
  - tag: package-2021-07-01
  - tag: package-2021-04-01
  - tag: package-2021-03-01-preview
  - tag: package-2020-04-01
  - tag: package-2020-03-01
  - tag: package-2020-01-01
  - tag: package-2019-11-01
  - tag: package-2019-06-01
  - tag: package-2019-05-01
  - tag: package-2018-11-19
  - tag: package-2020-02-18-preview
  - tag: package-2018-03-preview
```

## Tag: package-2022-05-01 and go

These settings apply only when `--tag=package-2022-05-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2022-05-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2022-05-01/$(namespace)
```

## Tag: package-2022-02-01-preview and go

These settings apply only when `--tag=package-2022-02-01-preview --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2022-02-01-preview' && $(go)
output-folder: $(go-sdk-folder)/services/preview/$(namespace)/mgmt/2022-02-01-preview/$(namespace)
```

## Tag: package-2022-01-01-preview and go

These settings apply only when `--tag=package-2022-01-01-preview --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2022-01-01-preview' && $(go)
output-folder: $(go-sdk-folder)/services/preview/$(namespace)/mgmt/2022-01-01-preview/$(namespace)
```

## Tag: package-2021-07-01 and go

These settings apply only when `--tag=package-2021-07-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2021-07-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2021-07-01/$(namespace)
```

## Tag: package-2021-04-01 and go

These settings apply only when `--tag=package-2021-04-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2021-04-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2021-04-01/$(namespace)
```

## Tag: package-2021-03-01-preview and go

These settings apply only when `--tag=package-2021-03-01-preview --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2021-03-01-preview' && $(go)
output-folder: $(go-sdk-folder)/services/preview/$(namespace)/mgmt/2021-03-01-preview/$(namespace)
```

## Tag: package-2020-04-01 and go

These settings apply only when `--tag=package-2020-04-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2020-04-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2020-04-01/$(namespace)
```

## Tag: package-2020-03-01 and go

These settings apply only when `--tag=package-2020-03-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2020-03-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2020-03-01/$(namespace)
```

## Tag: package-2020-01-01 and go

These settings apply only when `--tag=package-2020-01-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2020-01-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2020-01-01/$(namespace)
```

## Tag: package-2019-11-01 and go

These settings apply only when `--tag=package-2019-11-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2019-11-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2019-11-01/$(namespace)
```

## Tag: package-2019-06-01 and go

These settings apply only when `--tag=package-2019-06-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2019-06-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2019-06-01/$(namespace)
```

### Tag: package-2019-05-01 and go

These settings apply only when `--tag=package-2019-05-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2019-05-01' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2019-05-01/$(namespace)
```

### Tag: package-2018-11-19 and go

These settings apply only when `--tag=package-2018-11-19 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2018-11-19' && $(go)
output-folder: $(go-sdk-folder)/services/$(namespace)/mgmt/2018-11-19/$(namespace)
```

### Tag: package-2020-02-18-preview and go

These settings apply only when `--tag=package-2020-02-18-preview --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2020-02-18-preview' && $(go)
output-folder: $(go-sdk-folder)/services/preview/$(namespace)/mgmt/2020-02-18-preview/$(namespace)
```

### Tag: package-2018-03-preview and go

These settings apply only when `--tag=package-2018-03-preview --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

```yaml $(tag)=='package-2018-03-preview' && $(go)
output-folder: $(go-sdk-folder)/services/preview/$(namespace)/mgmt/2018-03-01-preview/$(namespace)
```
