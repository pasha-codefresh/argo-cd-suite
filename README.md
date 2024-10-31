# Argo Suite

A comprehensive repository of ArgoCD configurations for testing, development, and contribution. This project is structured to organize different aspects of ArgoCD, including configurations, application sets, notifications, and application templates.

## Project Structure

```plaintext
argo-suite/
├── README.md                # Overview of the project, instructions, and guidelines.
├── configs/                 # Configuration settings, ConfigMaps, and ArgoCD settings.
│   ├── argocd-configmaps/   # Different config maps specific to ArgoCD
│   │   ├── argocd-cm.yaml
│   │   ├── argocd-rbac.yaml
│   │   └── argocd-ssh-known-hosts-cm.yaml
│   └── notifications/       # Notification-related ConfigMaps
│       ├── notifier-config.yaml
│       └── templates.yaml
├── applicationsets/         # ApplicationSets for deploying multiple applications
│   ├── appset1.yaml
│   └── appset2.yaml
├── applications/            # Standard applications and templates
│   ├── app1.yaml
│   └── app2.yaml
└── crds/                    # Custom Resource Definitions (CRDs) for ArgoCD
    ├── applications-crd.yaml
    ├── applicationset-crd.yaml
    └── notifications-crd.yaml
