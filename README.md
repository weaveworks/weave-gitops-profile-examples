# Weave GitOps Enterprise Examples and Information
This repository contains examples for Weave GitOps Enterprise. Included are Cluster API templates, bootstrap configurations, and very simple profiles. These resources are used for demonstration and trial purposes, and are ***not suitable for production use.***

The profiles profile index can be used as examples of how to construct a Weave GitOps Enterprise profile and repository.

For information or a demonstration, contact Weaveworks sales@weave.works

# The "How To" Guide for a Weave GitOps Enterprise trial

Pre-requisites
A License/Entitlement Key from Weaveworks
A GitHub account (the best method to ensure success is to use a GitHub token. This resolves any authentication requirements. Creating a personal access token)
kubectl installed - instructions
A Kubernetes cluster.  For the example installation, we use kind which requires Docker.

Docker Instructions
“Kind” Cluster Instructions
Getting Started
https://docs.gitops.weave.works/docs/getting-started
Complete steps 1 and 2 in the Prepare Your Cluster section

Then continue with How to: Upgrade to Weave Gitops Enterprise
https://docs.gitops.weave.works/docs/enterprise/upgrading

For the Install a CAPI provider section, specific information and/or credentials may be required for your chosen provider. The documentation for the current Cluster API providers is here. For testing during the trial, Weaveworks recommends using a Kind cluster.

Additional, but optional, configuration steps to utilize a full SQL database (Postgres) can be performed.
https://docs.gitops.weave.works/docs/enterprise/configuration

