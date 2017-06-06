# Logic
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for Logic.



---
## Getting Started 
To build the SDK for Logic, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration for generating APIs


---
#### Basic Information 
These are the global settings for the Logic API.

``` yaml
# common 
title: Logic
description: Logic Client
tag: 2016-06-01

```


# Tag: 2016-06-01

These settings apply only when `--tag=2016-06-01` is specified on the command line.

``` yaml $(tag) == '2016-06-01'
input-file:
- Microsoft.Logic/2016-06-01/logic.json

```
 
# Tag: 2015-08-01-preview

These settings apply only when `--tag=2015-08-01-preview` is specified on the command line.

``` yaml $(tag) == '2015-08-01-preview'
input-file:
- Microsoft.Logic/2015-08-01-preview/logic.json

```
 
# Tag: 2015-02-01-preview

These settings apply only when `--tag=2015-02-01-preview` is specified on the command line.

``` yaml $(tag) == '2015-02-01-preview'
input-file:
- Microsoft.Logic/2015-02-01-preview/logic.json

```


---
#### Language-specific settings: CSharp

These settings apply only when `--csharp` is specified on the command line.

``` yaml $(csharp)
csharp:
  # override the default output folder
  output-folder: $(output-folder)/csharp
```
