# Docker

## Introduction

Docker is a container technology.

Unlike hypervisors, docker is not meat to virtualize and run different operating systems and kernels on the same hardware.

The main purpose of docker is to containerize applications and to ship them and run them.

![image-20200730133805274](image-20200730133805274.png)

## Containers vs. Virtual Machines

![image-20200730134042822](image-20200730134042822.png)

- VM:

  Advantages: Fully independent and isolated environment. You can host both Windows OS and Linux OS on the same hypervisor host.

  Disadvantages: Independent OS with higher overhead. Large and slow.

- Container:

  Advantages: Only contains applications and its necessary liberaries and dependencies. Fast and easy to scale.

  Disadvantages: Less isolation as more resources are shared in the kernel. You can host only one type of OS on the same docker host.

## How does it work?

Docker Hub --> Local

<img src="image-20200730171151197.png" alt="image-20200730171151197" style="zoom:25%;" />

Container vs. image

<img src="image-20200730171245848.png" alt="image-20200730171245848" style="zoom:25%;" />

## Continuous Delivery





# Kubernetes

## Introduction

It is a container orchestration technology used to orchestrate the deployment and management of hundreds and thousands of containers in a cluster environment.

## Architecture

### Nodes (Minions)

### Cluster

### Master

### Components

<img src="image-20200730190540687.png" alt="image-20200730190540687" style="zoom:50%;" />

#### API server

#### etcd

#### kubelet

#### Container Runtime

#### Controller

#### Scheduler

## PODs

## Replica Sets

## Deployments

## Networking

## Services