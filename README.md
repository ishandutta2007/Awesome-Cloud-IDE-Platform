# Awesome-Cloud-IDE-Platform

## Top Cloud IDE Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Browser-Based Development Environments, Remote Workspaces, Ephemeral Dev Containers, Collaboration & Self-Hosted Cloud Development*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud IDEs** (cloud development environments). These systems provide ready-to-code workspaces in the browser or remote clients, often with prebuilds, collaboration, and integration with Git providers.



**Examples** include Gitpod, CodeSandbox, Coder, Replit, StackBlitz, JetBrains CodeCanvas, Eclipse Che, GitHub Codespaces, Codeanywhere, and Daytona (the category leaders).



**Open-source emphasis**: Cloud development environments have strong open options. **Coder**, **Gitpod** (open components / Flex), **Eclipse Che**, **Eclipse Theia**, and **code-server** enable self-hosted, infrastructure-controlled remote IDEs. This section heavily expands those projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Gitpod](https://www.gitpod.io/)**  

  Cloud development environment platform (with self-hosted Flex options)—automated, Git-triggered workspaces, VS Code/JetBrains support, and prebuilds. Note: product direction has evolved toward agent-focused offerings; verify current managed vs self-hosted status.



- **[CodeSandbox](https://codesandbox.io/)**  

  Browser-based development environment focused on rapid prototyping, collaboration, and JavaScript/TypeScript ecosystems.



- **[Coder](https://coder.com/)**  

  Self-hosted and enterprise cloud development environment platform—Terraform-defined workspaces, secure remote access, and support for AI coding agents.



- **[Replit](https://replit.com/)**  

  Popular cloud IDE and AI-assisted development platform with instant environments, collaboration, and built-in deployment for learning and prototyping.



- **[StackBlitz](https://stackblitz.com/)**  

  Browser-native development environment powered by WebContainers—fast frontend and full-stack prototyping without local setup.



- **[JetBrains CodeCanvas](https://www.jetbrains.com/codecanvas/)**  

  JetBrains cloud development environment offering for remote IntelliJ-based workspaces and team development.



- **[Eclipse Che](https://www.eclipse.org/che/)**  

  Kubernetes-native open-source cloud development environments for enterprise teams (also available with commercial support paths).



- **[GitHub Codespaces](https://github.com/features/codespaces)**  

  Fully managed cloud development environments tightly integrated with GitHub—VS Code in the browser or desktop, devcontainers, and GitHub Copilot.



- **[Codeanywhere](https://codeanywhere.com/)**  

  Cloud IDE and remote development platform supporting multiple environments and collaboration features.



- **[Daytona](https://www.daytona.io/)**  

  Development environment management platform focused on consistent, secure, and scalable remote workspaces.



## Open-Source GitHub Projects

- **[Coder](https://github.com/coder/coder)**  

  Leading open-source platform for self-hosted cloud development environments—Terraform-defined workspaces, secure tunnels, idle shutdown, and support for VS Code and AI agents.



- **[Gitpod](https://github.com/gitpod-io/gitpod)**  

  Open-source developer platform for on-demand cloud development environments (with self-hosted deployment options)—prebuilds, VS Code/JetBrains, and Git provider integration.



- **[Eclipse Che](https://github.com/eclipse-che/che)**  

  Kubernetes-based open-source cloud development environment platform for enterprise teams—workspaces defined and orchestrated on Kubernetes.



- **[Eclipse Theia](https://github.com/eclipse-theia/theia)**  

  Open-source cloud and desktop IDE framework (TypeScript)—extensible platform that powers many browser-based IDEs and supports VS Code extensions.



- **[code-server](https://github.com/coder/code-server)**  

  Open-source project that runs VS Code on a remote server and exposes it in the browser—widely used for self-hosted remote development.



- **[DevPod](https://github.com/loft-sh/devpod)**  

  Open-source tool for creating development environments that can run on any infrastructure (local, remote, cloud) using standard container/devcontainer specs.



- **[OpenVSCode Server / related VS Code web projects](https://github.com/)**  

  Community and vendor efforts to run VS Code in the browser on self-hosted infrastructure.



- **[Workspace and devcontainer open standards](https://github.com/devcontainers)**  

  Open specifications and tools for defining portable development environments used by Codespaces, Coder, Gitpod, and others.



- **[Self-hosted IDE marketplace and extension open tools](https://github.com/)**  

  Projects that enable private extension marketplaces for air-gapped or restricted cloud IDE deployments.



- **[Documentation and cloud-IDE open playbooks](https://coder.com/docs)**  

  Guides for deploying Coder, Gitpod Flex, Eclipse Che, or code-server on your own infrastructure.



### Additional Strong Open-Source Options

- Deploying **Coder** for Terraform-defined, self-hosted developer workspaces with strong security and cost control.

- Using **Gitpod** open components or **Eclipse Che** for Kubernetes-native cloud development environments.

- Running **code-server** or **Theia** when a lightweight browser VS Code experience is sufficient.

- Accepting that fully managed convenience, deep GitHub integration, AI agents, and polished multiplayer still favor commercial offerings (GitHub Codespaces, Replit, StackBlitz, CodeSandbox, JetBrains CodeCanvas, etc.).

- Focusing open-source efforts on data residency, infrastructure ownership, and standardized remote development.



**Frameworks for building custom systems**: Define workspaces with Terraform or devcontainers → provision via Coder/Gitpod/Che → connect via secure tunnels or browser → integrate with Git and CI. Suitable for platform teams and enterprises. Many developers still use managed cloud IDEs for zero-ops convenience.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud IDEs run code and may access repositories and secrets. Open-source self-hosted deployments require proper security, network isolation, and access control. This list is not security advice.



---

**Made for developers, platform engineers, and open-source remote-development advocates.**

Let's keep coding environments portable, secure, and as open as practical.
