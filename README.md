# ShellOps - Server Management Assistance

## Product comparison

- ### ShellOps

  - Persona: Software developers, Webmasters
  - Interoperability: Low
  - Cloud availability: AWS, Azure, GCP
  - Communication: With client using SSH
  - Two way communication
  - (+) Easy setup
  - (+) Easy to operate
  - (-) Few recipes

- ### Ansible

  - Persona: DevOps
  - Interoperability: High
  - Cloud availability: AWS, Azure, GCP
  - Communication: SSH
  - One way communication
  - Suitable for large organizations
  - (+) in yaml
  - (+) large recipe
  - (+) community
  - (+) no client agent required
  - (-) performance comparing to other tools in list
  - (-) yaml is not flexible

- ### Puppet

  - Persona: DevOps
  - Cloud availability: AWS, Azure
  - Interoperability: High
  - Declarative
  - Ruby and DSL
  - Communication: SSL ( rest api ? )
  - Two way communication
  - Suitable for large organizations
  - (+) community
  - (+) reporting to understand infs
  - (-) Learning curve + Ruby

- ### Chef

  - Persona: DevOps
  - Cloud availability: AWS
  - Interoperability: High
  - Communication: Knife tool ( custom client )
  - Procedural
  - Two way communication
  - Suitable for large organizations
  - (+) Large recipe collection
  - (+) Integrates with Git
  - (-) Learning curve + Ruby
  - (-) Main server does not have much control

- ### SaltStack

  - Persona: DevOps
  - Cloud availability: AWS
  - Interoperability: High
  - Declarative
  - Python, yaml and DSL
  - Communication: SSH
  - Two way communication
  - Suitable for large organizations
  - (+) Reporting
  - (+) Simple usage after setup
  - (-) Setup is hard
  - (-) UI is less developed than other
