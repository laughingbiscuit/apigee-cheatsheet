id: docs
# Apigee Cheatsheets

## Introduction

For each topic, a cheatsheet should show:
- A TL;DR for the topic
- Quick links to useful resources
- An example flow/entity diagram
- Commands to quickly demonstrate the concept

---

## What is API Management?

### What is an API?

An ['application programming interface'](https://docs.apigee.com/api-platform/get-started/basic-concepts) is an interface that makes it easy for one application to 'consume' capabilities or data from another application.

![https://www.youtube.com/watch?v=TbVtliFXOOY](https://youtube.com)

### APIs as Products?

#### The API Product Mindset

![https://www.youtube.com/watch?v=jng8mvb3eB4](https://youtube.com)

#### The API Product Deconstructed

![https://www.youtube.com/watch?v=0jfaqkpm-ts](https://youtube.com)

### Developer Experience

- In 5 seconds, the developer should know what an API does
- In 5 minutes, the developer should have make a successful request
- In 5 days, the developer should have taken their app to production

If they cannot use your APIs, they will look elsewhere.

### Features of API Management

- Analytics
- Traffic Management
- Developer Engagment
- Monetization
- Security
- Orchestration
- Mediation

---

## Apigee Product Overview

![Services](https://docs.apigee.com/api-platform/images/EdgeServices_v3.png)

---

## Choosing the first API Use Case

TODO

### Identity

All use cases require some form of identity. We must identify whether to use API Keys, one of the OAuth 2 grant types, Open ID Connect etc.

### Business Value

TODO

---

## Methodology

TODO

### Building an API Team

TODO

### User Stories

TODO

### DoR and DoD

TODO

### Example Backlog

TODO

---

## Development Environment Setup

TODO

### Local Tools

TODO

### Remote Tools

- Git
- Node JS
- Maven
- Apigee Edge Environment
- Logging

---

## Continuous Integration

[Demo](https://github.com/apigee/maven-jenkins-ci-demo)

### Build and Deploy Tools

- UI
- Management API
- apigeetool
- Maven Plugin

### Linting

- eslint
- bundle-linters

### Unit Testing

- junit
- mocha

### Integration Testing

- apickli

### Performance Benchmarking

- apachebench

### Dev Portal Publishing

- d8 rest api

### Publish Results and Notify

- jenkins reports
- email + slack notifications

---

## Edge Design and Provisioning

TODO

### Organizations and Environments

[Design](https://community.apigee.com/questions/22800/how-have-you-setup-your-orgenv-combos.html)

### Physical Separation

- Regions
- Traffic Isolation
- PCI + HIPAA

---

## Microgateway Design and Installation

TODO

### Organizations and Environments

TODO

### Deployment Options

TODO

---

## Private Cloud Design and Installation

TODO

### Topology Design

- Reference Topologies
- Estimator
- etp

### Installation and Provisioning

- shell scripts
- ansible 

---

## RESTful API Design

TODO

---

## Mocking

- swagger mock
- apimocker
- assign message

---

## Behaviour Driven Development

- [apickli](https://github.com/apickli/apickli.git)

---

## Traffic Management

- spike vs quota

---

## Analytics

- out of the box
- stats collector
- custom reports
- async reports

---

## Identity

(int/ext generated)
- API Key
- Basic Auth
- OAuth 2
  - Client Credentials
  - Password
  - Auth Code
  - Implicit
- OIDC
  - auth code
  - implicit
  - hybrid
- Extensions
  - proof of possession
  - pkce
  - device flow
  - eidas
  - token by SAML
- SAML

---

## Security

- TLS
- Audit
- RBAC
- Content Based Protection
- Traffic Mgmt
- SIEM integration

---

## Mediation

TODO

---

## Orchestration

TODO

---

## Developer Portal

- Integrated
- D7
- D8
- Roll your own

---

## Monetization

TODO

