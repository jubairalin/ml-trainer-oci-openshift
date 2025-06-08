# ml-trainer-oci-openshift
Machine Learning Trainer on OpenShift with OCI &amp; GitHub Actions
This repository provides a full CI/CD pipeline for training and testing a machine learning model using Python, running on OpenShift Kubernetes clusters hosted on Oracle Cloud Infrastructure (OCI). It includes Dockerized training scripts, Kubernetes job manifests, unit tests, GitHub Actions workflows for CI/CD, and integration with OCI Object Storage for model uploads. It follows GitOps best practices using ArgoCD for deployment automation.

This includes:

Kubernetes job YAMLs (training/testing)

Dockerfile

CI/CD workflows

Python training script

Unit tests

PVCs and OCI secrets integration
