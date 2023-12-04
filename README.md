# OSS Applications

This is a GitOps repo that acts as the source of truth for the open source team at Codefresh demoing GitOps apps. 

# Directory Structure

```bash
├── README.md
├── base
│   ├── deployment.yaml
│   ├── kustomization.yaml
│   └── service.yaml
└── overlays
    └── development
        ├── development
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   ├── setting.yaml
        │   └── version.yaml
        ├── production
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   ├── setting.yaml
        │   ├── replicas.yaml
        │   └── version.yaml
        ├── staging
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   ├── setting.yaml
        │   ├── replicas.yaml
        │   └── version.yaml
```


# Useful Links about Codefresh, Argo, and GitOps
* [Codefresh GitOps](https://codefresh.io/product/)
* [About Argo CD](https://codefresh.io/learn/argo-cd/)
* [About Argo Rollouts](https://codefresh.io/learn/argo-rollouts/)
* [About GitOps Directory Structures](https://codefresh.io/blog/how-to-model-your-gitops-environments-and-promote-releases-between-them/)
* [Open GitOps](https://opengitops.dev/)
* [GitOps Certification and Training for Argo CD](https://codefresh.io/argo/get-certified)