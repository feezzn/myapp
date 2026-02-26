# 🚀 MyApp — Kubernetes Application (GitOps)

Este repositório contém a aplicação **MyApp**, empacotada como manifests Kubernetes e implantada automaticamente em um cluster **Amazon EKS** via **Argo CD (GitOps)**.

O objetivo é simular um fluxo real de trabalho, onde o time de desenvolvimento mantém o código/manifests da aplicação e a plataforma (infra + deploy) é gerenciada de forma declarativa.

---

## 🧠 Visão Geral

- Aplicação de exemplo baseada em **NGINX**
- Manifests Kubernetes simples (`Deployment` + `Service`)
- Deploy automatizado via **Argo CD**
- Cluster de destino: **EKS (AWS)**
- Namespace dedicado: `myapp`

---

## 🧱 Estrutura do Repositório

```text
myapp/
└── k8s/
    ├── deployment.yaml
    └── service.yaml

```

👨‍💻 Autor

Felipe
DevOps / Site Reliability Engineer

Projeto criado para estudo e prática de Kubernetes, GitOps e plataforma em nuvem ☁️