# Playing with Argo suite and Crossplane on Kind kubernetes cluster

* [Argo CD](https://argo-cd.readthedocs.io/en/stable/) is a declarative, GitOps continuous delivery tool for Kubernetes.
* [Argo Rollouts](https://argoproj.github.io/argo-rollouts/) is a Kubernetes controller and set of CRDs which provide advanced deployment capabilities such as blue-green, canary, canary analysis, experimentation, and progressive delivery features to Kubernetes.
* [Argo Workflows](https://argo-workflows.readthedocs.io/en/stable/) is an open source container-native workflow engine for orchestrating parallel jobs on Kubernetes.
* [Argo Events](https://argoproj.github.io/argo-events/) is an event-driven workflow automation framework for Kubernetes which helps you trigger K8s objects, Argo Workflows, Serverless workloads, etc. on events from a variety of sources like webhooks, S3, schedules, messaging queues, gcp pubsub, sns, sqs, etc.
* [Crossplane](https://www.crossplane.io/) is an open source Kubernetes extension that transforms your Kubernetes cluster into a universal control plane.

## Tasks

Using [Task](https://taskfile.dev/):

```bash
$ task --list-all
task: Available tasks for this project:
* argocd:              Install ArgoCD
* argocli:             Install Argo CLI
* argorollouts:        Install Argo Rollouts
* argoworkflows:       Install Argo Workflows
* crossplane:          Install Crossplane
* default:             Main task
* destroy:             Destroy the kubernet cluster
* ingress:             Deploy NGINX Ingress Controller
* kind-cluster:        Create the kubernet cluster using Kind
* metallb:             Install bare metal load-balancer for Kubernetes
```