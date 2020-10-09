---
title: "Welcome to cert-manager"
linkTitle: "Welcome to cert-manager"
weight: 10
type: "docs"
---

cert-manager is a native [Kubernetes](https://kubernetes.io) certificate
management controller. It can help with issuing certificates from a
variety of sources, such as [Let's Encrypt](https://letsencrypt.org),
[HashiCorp Vault](https://www.vaultproject.io),
[Venafi](https://www.venafi.com/), a simple signing key pair, or self
signed.

Use cert-manager to ensure that certificates are valid and current, and can even 
renew certificates at a configured time before they expire.

It is loosely based upon the work of
[kube-lego](https://github.com/jetstack/kube-lego) and has borrowed some
wisdom from similar projects such as
[kube-cert-manager](https://github.com/PalmStoneGames/kube-cert-manager).

![High level overview diagram explaining cert-manager architecture](/images/high-level-overview.svg)

This is the full technical documentation for the project, and should be
used as a source of references when seeking help with the project.
