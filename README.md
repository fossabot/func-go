# Go Func Runtime
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fknative-extensions%2Ffunc-go.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fknative-extensions%2Ffunc-go?ref=badge_shield)


This repository contains the function invocation and runtime framework for 
Knative Go functions.

## Overview

Knative Go functions are a way to run Go code in a serverless environment. The
functions are invoked by the Knative runtime, which provides the function with
an event and a context. The function then processes the event and returns a
result.

## Getting started

Typically, this runtime is used in the context of a Knative Go function. You
can create a new function using the Knative Go function template.

```
func create -l go --builder=host
```

This will create a new Go project that uses the Knative Go function invocation
framework. You can then build and deploy the function using the Knative
Functions CLI.

```
func deploy
```

## More information

For more information about Knative Go functions, see the
[Knative Functions documentation](https://knative.dev/docs/functions/).


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fknative-extensions%2Ffunc-go.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fknative-extensions%2Ffunc-go?ref=badge_large)