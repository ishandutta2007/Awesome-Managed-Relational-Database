# Awesome-Managed-Relational-Database

## Top Managed OpenShift Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Enterprise Kubernetes, Managed OpenShift, Hybrid Cloud Container Platforms & Production-Grade Cluster Management*

**Last updated: October 2026**



This repository tracks notable **SaaS / managed platforms** and **open-source projects** for **Managed OpenShift and enterprise Kubernetes platforms**. These solutions provide production-ready container orchestration with enterprise features, multi-cluster management, security, and cloud-native tooling—often built on or compatible with OpenShift and Kubernetes.



**Examples** include Azure Red Hat OpenShift, Red Hat OpenShift Dedicated, Red Hat OpenShift Service on AWS (ROSA), Red Hat OpenShift on IBM Cloud, OKD, VMware Tanzu, Rancher, Mirantis Kubernetes Engine, Canonical Charmed Kubernetes, and Google Cloud Anthos (the category leaders).



**Open-source emphasis**: The foundation of these platforms is open source. **OKD** (the community distribution of OpenShift), **Kubernetes**, **Rancher**, and related projects form the core. This section is heavily expanded with every major active project.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Azure Red Hat OpenShift](https://azure.microsoft.com/products/openshift/)**  

  Fully managed OpenShift service jointly operated by Microsoft and Red Hat on Azure, with integrated Azure billing, identity, and networking.



- **[Red Hat OpenShift Dedicated](https://www.redhat.com/en/technologies/cloud-computing/openshift/dedicated)**  

  Red Hat’s managed OpenShift offering running on public cloud infrastructure with enterprise support and SLAs.



- **[Red Hat OpenShift Service on AWS (ROSA)](https://aws.amazon.com/rosa/)**  

  Managed OpenShift service on AWS, co-engineered by Red Hat and Amazon, with native AWS integrations and joint support.



- **[Red Hat OpenShift on IBM Cloud](https://www.ibm.com/cloud/openshift)**  

  Managed OpenShift service on IBM Cloud with deep integration into IBM’s hybrid cloud and AI portfolio.



- **[VMware Tanzu](https://tanzu.vmware.com/)**  

  Enterprise Kubernetes platform with multi-cloud management, application services, and strong VMware ecosystem integration.



- **[Rancher (SUSE Rancher)](https://www.rancher.com/)**  

  Multi-cluster Kubernetes management platform (commercial support available) used widely for managing both on-prem and cloud Kubernetes/OpenShift-like environments.



- **[Mirantis Kubernetes Engine](https://www.mirantis.com/software/mirantis-kubernetes-engine/)**  

  Enterprise Kubernetes distribution and management platform evolved from Docker Enterprise, with strong container runtime and security focus.



- **[Canonical Charmed Kubernetes](https://ubuntu.com/kubernetes)**  

  Canonical’s enterprise Kubernetes offering with model-driven operations via Juju and Ubuntu-based support.



- **[Google Cloud Anthos](https://cloud.google.com/anthos)**  

  Google’s hybrid and multi-cloud application platform built on Kubernetes, enabling consistent management across environments.



- **[Other managed OpenShift / enterprise Kubernetes services](https://www.redhat.com/en/technologies/cloud-computing/openshift)**  

  Additional cloud-provider and partner-managed OpenShift and Kubernetes offerings with enterprise support contracts.



## Open-Source GitHub Projects

- **[OKD](https://github.com/okd-project/okd)**  

  The community distribution of OpenShift—fully open-source Kubernetes distribution with the same core technology as Red Hat OpenShift.



- **[Kubernetes](https://github.com/kubernetes/kubernetes)**  

  The foundational open-source container orchestration platform that underpins OpenShift, Rancher, Tanzu, Anthos, and virtually all modern managed platforms.



- **[OpenShift Origin / OKD-related components](https://github.com/openshift)**  

  Upstream OpenShift projects including the installer, console, operators, and supporting tools that power both OKD and commercial OpenShift.



- **[Rancher](https://github.com/rancher/rancher)**  

  Open-source multi-cluster Kubernetes management platform that can manage vanilla Kubernetes, RKE, and other distributions.



- **[RKE / RKE2](https://github.com/rancher/rke2)**  

  Rancher’s lightweight, secure Kubernetes distribution designed for simplicity and security.



- **[k3s](https://github.com/k3s-io/k3s)**  

  Lightweight certified Kubernetes distribution from Rancher, ideal for edge, IoT, and resource-constrained environments.



- **[KubeVirt](https://github.com/kubevirt/kubevirt)**  

  Open-source project that extends Kubernetes to run virtual machines alongside containers—used in some OpenShift and enterprise setups.



- **[Operators and Operator Framework](https://github.com/operator-framework)**  

  Open-source tools for building and managing Kubernetes operators, heavily used in the OpenShift ecosystem.



- **[Documentation and OKD / Kubernetes guides](https://okd.io/)**  

  Resources for deploying and operating community OpenShift (OKD) and pure Kubernetes clusters.



- **[Cluster API and multi-cluster management tools](https://github.com/kubernetes-sigs/cluster-api)**  

  Open-source declarative APIs and tools for provisioning, upgrading, and managing Kubernetes clusters across environments.



### Additional Strong Open-Source Options

- Deploying **OKD** as the closest open-source equivalent to commercial OpenShift.

- Using pure **Kubernetes** with operators and GitOps tools for maximum flexibility.

- Managing fleets with **Rancher** or Cluster API-based tooling.

- Combining **k3s / RKE2** for edge or simpler deployments.

- Accepting that fully managed services (ARO, ROSA, OpenShift Dedicated, Anthos, Tanzu) still dominate for enterprise SLAs, compliance, and reduced operational burden.

- Focusing open-source efforts on control, cost efficiency, and avoiding proprietary lock-in while retaining OpenShift-compatible workflows.



**Frameworks for building custom systems**: Start with OKD or upstream Kubernetes → add operators and the OpenShift console components as needed → manage with Rancher or Cluster API → apply GitOps (Argo CD / Flux). Suitable for organizations that want OpenShift-like capabilities without managed service costs. Many enterprises still choose ROSA, ARO, or OpenShift Dedicated for production support and compliance.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/managed or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Managed Kubernetes and OpenShift platforms involve complex security, networking, and compliance requirements. Self-hosted solutions demand significant operational expertise. This list is not architecture or support advice.



---

**Made for platform engineers, SREs, and cloud-native architects.**

Let's keep enterprise container platforms powerful, flexible, and as open as practical.
