# Vault-Kubernetes-Deploy
Gestión Segura de Secretos en Kubernetes: Despliegue Manual de HashiCorp Vault con TLS.

Este repositorio detalla un despliegue de HashiCorp Vault en Kubernetes, priorizando la seguridad y el control granular. Se demuestra la configuración de Vault con TLS (usando certificados autofirmados) y persistencia de datos mediante Persistent Volumes, todo a través de manifiestos YAML de Kubernetes, ofreciendo una alternativa educativa al uso de Helm.

## Arquitectura del Despliegue de Vault

A continuación, se presenta un diagrama conceptual del despliegue de HashiCorp Vault en nuestro clúster de Kubernetes, mostrando la encriptación TLS y la persistencia de secretos.

[Diagrama de Despliegue de Vault en Kubernetes](assets/vault-kubernetes-diagram-deploy.png)
