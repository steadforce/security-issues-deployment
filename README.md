# Security Issues-Deployment

Kubernetes deployment manifests for the security issues frontend and backend apps.

## Local testing

### Prerequisites
 
- Local K8s Cluster built from https://gitea.cloud01.intern.steadforce.com/Playground/SteadOps-Steadies-K8s-Workplace
- Kubectl and helm setup either using the workbench or by using a local setup

### Running it

Point your browser to `https://backend-security-issues.steadops.local.steadforce.com/swagger/index.html` and `https://frontend-security-issues.steadops.local.steadforce.com/`.
Ensure that those hostnames are set in your local `etc/hosts` file (Linux, Mac) or in
`%SystemRoot%\System32\drivers\etc\hosts` (Win).