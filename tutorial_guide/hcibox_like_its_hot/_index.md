
## Overview

![cover selected](./img/headshot.jpg)

### Drop Details
The drop author, a pale dude

## Prerequsities

- ### Review HCIBox documentation
  ```shell
  az ad sp show
  ```
      

## Getting Started
### Run this script on your VM.
Run this script.
```shell
az ad sp show --query id -o tsv
```

## Development Artifacts
### 
PowerShell code
```shell
param (     [string]$adminUsername,     [string]$adminPassword,     [string]$spnClientId,     [string]$spnClientSecret,     [string]$tenantId,     [string]$spnAuthority,     [string]$subscriptionId,     [string]$resourceGroup,     [string]$azdataUsername,     [string]$azdataPassword,     [string]$acceptEula,     [string]$registryUsername,     [string]$registryPassword,     [string]$arcDcName,     [string]$azureLocation,     [string]$mssqlmiName,     [string]$POSTGRES_NAME,     [string]$POSTGRES_WORKER_NODE_COUNT,     [string]$POSTGRES_DATASIZE,     [string]$POSTGRES_SERVICE_TYPE,     [string]$
```

## Resource

![resource selected](./img/Screenshot 2024-03-02 093843.png)


    