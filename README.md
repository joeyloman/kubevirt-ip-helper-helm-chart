# kubevirt-ip-helper Helm Chart

## Prerequisites

- Helm 3.x

## Adding the Chart

```SH
helm repo add kubevirt-ip-helper https://joeyloman.github.io/kubevirt-ip-helper-helm-chart
helm repo update
```

## Installing the Chart

```SH
helm install kubevirt-ip-helper kubevirt-ip-helper/kubevirt-ip-helper -n kubevirt-ip-helper --create-namespace
```

# License

Copyright (c) 2023 Joey Loman <joey@binbash.org>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
