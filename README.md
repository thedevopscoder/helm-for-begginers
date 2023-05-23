# Welcome to Helm for beginners 👋
![Alt Text](.img/helm%20flow.drawio.png)
<!-- <img src=".img/helm%20flow.drawio.png" alt="Alt Text" width="600" align="center" /> -->

This repository provides a walkthrough on Helm, covering topics such as Helm components, Helm charts, working with Helm, customizing chart parameters, lifecycle management, writing a chart, ensuring chart functionality, functions, and more.

<br>

## Pre-requisites 👍

Pre-requisites for the is repo are Access to a Kubernetes/K8 cluster. Have no fear if you do not have access to a k8 cluster. You can create one easily by installing one of the following Kubernetes distributions tools such as minikube, k3d or kind. Details on Kubernetes distributions installers can be found below.

<br>

## Kubernetes Distribution Tools
<details>
  <summary>Kubernetes distributions installers</summary>
  <br>

  # K3d

  k3d is a lightweight wrapper to run k3s (Rancher Lab’s minimal Kubernetes distribution) in docker.

  You can install K3D via :-

  #### Chocolatey
  ```
  choco install k3d
  ```
  For k3 cluster management check out vscode extension [vscode-k3d](https://github.com/k3d-io/vscode-k3d).

  VS Code quick install below.
  ```
  code --install-extension inercia.vscode-k3d
  ```
  #### Homebrew (macOS)
  ```
  brew install k3d
  ```
  More K3d install options can be found [here](https://k3d.io/v5.5.1/#installation).


  # minikube

  minikube is local Kubernetes, focusing on making it easy to learn and develop for Kubernetes.

  You can install minikube via :-

  #### Chocolatey
  ```
  choco install minikube
  ```

  #### Homebrew (macOS)
  ```
  brew install minikube
  ```

  More minikube install options can be found [here](https://minikube.sigs.k8s.io/docs/start/).

  # kind

  kind is a tool for running local Kubernetes clusters using Docker container “nodes”. kind was primarily designed for testing Kubernetes itself, but may be used for local development or CI.
  You can install kind via :-

  #### Chocolatey
  ```
  choco install kind
  ```

  #### Homebrew (macOS)
  ```
  brew install kind
  ```
  More kind install options can be found [here](https://kind.sigs.k8s.io/docs/user/quick-start/).

</details>



