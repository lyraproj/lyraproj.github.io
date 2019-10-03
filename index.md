![Lyra logo](assets/lyrabanner.png)

# What is Lyra?
Lyra (lee-ruh) is a github organization started by [Puppet](https://puppet.com) to collect open-source projects and repositories that work with cloud infrastructure. They're mostly written in Go and universally welcome issues, comments, and PRs!  Some highlights and places to get started:

* [WASH](https://github.com/puppetlabs/wash) - a Wide-Area SHell, which presents cloud resources in a unified, familiar shell-like interface
* [go-hiera](https://github.com/lyraproj/hiera) - A compact, clean implementation of Hiera (a hierarchical data store) for injecting values into configuration.
* [dgo](https://github.com/lyraproj/dgo) - "Dynamic Go", a dynamic data type library that enables input validation and type checking


# What _was_ Lyra?
Lyra, the project, was originally intended to be an open source workflow engine for provisioning and managing cloud native infrastructure. Using infrastructure as code, Lyra enabled you to declaratively provision and manage public cloud, private cloud, and other API-backed resources as well as orchestrate imperative actions. For more information, see the [README.md](https://github.com/lyraproj/lyra) in the main project repository.

As we developed Lyra, it became clear that the end-to-end workflow had a significant amount of overlap with other tools. The use cases for it are closely aligned with tools like Terraform and Pulumi as well as cloud native continuous delivery projects like Jenkins X, Tekton Pipelines, and Spinnaker. Rather than reinvent the wheel, we shifted to working upstream with existing projects and communities. The original codebase and project documentation are still available in the project repository.
