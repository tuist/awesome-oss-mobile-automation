# awesome-oss-mobile-automation

There is a lot happening around commoditizing automation for mobile devices through open source, but the various efforts are scattered across repositories and projects. This repository aims to serve as a directory to locate those efforts.

## Virtualization

### macOS Environments

- [Lume](https://github.com/trycua/lume): Create and run high-performance macOS and Linux VMs on Apple Silicon, with built-in support for AI agents.
- [Curie](https://github.com/macvmio/curie): CLI-oriented macOS virtual machine
- [Geranos](https://github.com/macvmio/geranos): Transfers macOS virtual machine images to and from OCI registries

## Orchestration

### macOS Environments

- [Fugaci](https://github.com/macvmio/fugaci): Kubernetes-based system for serving ephemeral macOS virtual machines (VMs)
- [buildkansen](https://github.com/tramlinehq/buildkansen): Fast, pooled macOS runners for GitHub Actions

## Release management

- [Tramline](https://github.com/tramlinehq/tramline): Release coordination and deployment platform, just for your mobile apps
- [Macige](https://github.com/tramlinehq/macige): Mobile App CI workflow GEnerator: Android, iOS, Flutter, and React Native!

## Dev environment management

- [Mise](https://github.com/jdx/mise): dev tools, env vars, task runner

## Automation DSLs and tools

- [swift-sh](https://github.com/mxcl/swift-sh): Easily script with third-party Swift dependencies.
- [Sake](https://github.com/kattouf/Sake): 🍶 Swift-based utility for managing project commands, inspired by Make.

## Infrastructure Automation Tools

- [Packer](https://github.com/hashicorp/packer): A tool for building identical machine images for multiple platforms from a single source configuration.
    - [Packer Plugin Parallels](https://github.com/Parallels/packer-plugin-parallels): The Parallels Packer Plugin is able to create [Parallels Desktop for Mac](https://www.parallels.com/products/desktop/) virtual machines and export them in the PVM format.
    - [Packer Plugin QEMU](https://github.com/hashicorp/packer-plugin-qemu): The QEMU Packer Plugin comes with a single builder able to create KVM virtual machine images.
    - [Packer Plugin Tart](https://github.com/cirruslabs/packer-plugin-tart): Packer builder for Tart VMs.
- [Ansible](https://github.com/ansible/ansible): Ansible offers open-source automation that is simple, flexible, and powerful.
    - [Ansible Role: osx-command-line-tools](https://github.com/elliotweiser/ansible-osx-command-line-tools): An Ansible role for installing OS X Command Line Tools
- [pyinfra](https://github.com/pyinfra-dev/pyinfra): pyinfra turns Python code into shell commands and runs them on your servers.
- [Terraform](https://github.com/hashicorp/terraform): Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently.

## Useful Examples

These projects contain examples of scripts and other automation setups to be used as inspiration for your own projects.

- [macos-image-templates](https://github.com/cirruslabs/macos-image-templates): Repository with Packer templates to build macOS [Tart](https://tart.run/) virtual machines to use with [Cirrus Runners](https://cirrus-runners.app/), [Cirrus CI](https://cirrus-ci.org/guide/macOS/) or [any other automation](https://tart.run/integrations/cirrus-cli/).
- [OS X templates for Packer and VeeWee](https://github.com/timsutton/osx-vm-templates/): This is a set of Packer templates and support scripts that will prepare an OS X installer media that performs an unattended install for use with [Packer](http://packer.io) and [VeeWee](http://github.com/jedi4ever/veewee).
- [`mkuser` for macOS](https://github.com/freegeek-pdx/mkuser): Make user accounts for macOS with many advanced options.
- [macAdminTools](https://github.com/brunerd/macAdminTools): Tools for the MacAdmin
- [runner-images](https://github.com/actions/runner-images): GitHub's repository containing scripts and tools for building up the images they provide for GitHub Actions. (See the [`images/macos/scripts/` directory](https://github.com/actions/runner-images/tree/main/images/macos/scripts) for their macOS-specific automation.)
