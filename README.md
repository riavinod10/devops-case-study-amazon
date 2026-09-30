# DevOps Case Study - Amazon (Q2)

## Architecture
Flask API -> Docker -> Kubernetes -> Prometheus/Grafana

## Pipeline Flow
GitHub Actions: Test -> Build Docker -> Push to GHCR -> Deploy to K8s

## Challenges
- Kube config secrets
- Image pull policy
- ServiceMonitor namespace selector
- Ansible Docker permissions

## Lessons Learned
Shift-left, automation, small releases, observability.