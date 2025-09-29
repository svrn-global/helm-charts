# Svrn Data-In-Motion (DIM) Sensor releases

There are the following components of the DIM Sensor:

| Component             | Kind       | Name               |
|-----------------------|------------|--------------------|
| **Digger**            | Deployment | `digger`           |
| **Interceptors**      | DaemonSet  | `interceptor`      |
| **Detection**         | Deployment | `detection-tool`   |
| **Kafka**             | Deployment | `kafka`            |           
|  **Prometheus agent** | Deployment | `prometheus-agent` |

Below you can find the release notes with changes in components and their versions. There is also the Helm chart version for each release.

If the component is not mentioned in the release notes, it means that there were no changes in it.

Versions of Digger and Interceptors are synchronized, but sometimes there are changes in one of them only. In this case, the component that has no changes is not mentioned in the release notes.

## DIM-25.3.2

Release date: Mar 28, 2025

### Versions

* **Digger**: 0.44.0
* **Interceptors**: 0.44.0
* **Detection**: 2.13.8
* **Helm chart**: 1.52.0

