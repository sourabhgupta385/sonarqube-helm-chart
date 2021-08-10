# SonarQube Helm Chart
A helm chart to install SonarQube on OpenShift 4.x

## Usage

- Clone the repository
- Install the helm chart

```bash
helm install sonarqube .
```
- To upgrade sonarqube helm release

```bash
helm upgrade sonarqube .
```

- To delete sonarqube instance

```bash
helm delete sonarqube
```
## Notes

- If PVC storage is increased then pod must be restarted