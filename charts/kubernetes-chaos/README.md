# kubernetes-chaos

![Version: 2.8.2](https://img.shields.io/badge/Version-2.8.2-informational?style=flat-square) ![AppVersion: 1.13.2](https://img.shields.io/badge/AppVersion-1.13.2-informational?style=flat-square)

A Helm chart to install litmus chaos experiments for kubernetes category (chaos-chart)

**Homepage:** <https://litmuschaos.io>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| ksatchit | karthik.s@mayadata.io |  |
| chandankumar4 | chandan.kumar@zopsmart.com |  |
| jasstkn | jasssstkn@yahoo.com |  |

## Source Code

* <https://github.com/litmuschaos/litmus>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| environment.containerPath | string | `"/var/lib/docker/containers"` |  |
| environment.runtime | string | `"docker"` |  |
| environment.socketPath | string | `"/var/run/docker.sock"` |  |
| experiments.disabled | list | `[]` |  |
| fullnameOverride | string | `"k8s"` |  |
| image.litmus.pullPolicy | string | `"Always"` |  |
| image.litmus.repository | string | `"litmuschaos/ansible-runner"` |  |
| image.litmus.tag | string | `"1.13.0"` |  |
| image.litmusGO.pullPolicy | string | `"Always"` |  |
| image.litmusGO.repository | string | `"litmuschaos/go-runner"` |  |
| image.litmusGO.tag | string | `"1.13.2"` |  |
| image.litmusLIBImage.repository | string | `"litmuschaos/go-runner"` |  |
| image.litmusLIBImage.tag | string | `"1.13.2"` |  |
| image.networkChaos.tcImage | string | `"gaiadocker/iproute2"` |  |
| image.pumba.libName | string | `"pumba"` |  |
| image.stressChaos.stressImage | string | `"gaiaadm/pumba"` |  |
| nameOverride | string | `"k8s"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)