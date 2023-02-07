# Platform (Dev-Ops) Tech Test

## Abstract

### Introduction

The purpose of this test is to provide a framework for which to discuss your technical abilities during the interview process. There is no 'correct' answer to solve, and no failure based wholly on this technical test. It is an opportunity for you to come up with some ideas in your own time if you so desire, or provide a skeleton on which a 'live' discussion can follow during the interview process.

### Task

After reviewing the scenario below, up to the level of consultant you are applying for, please define the infrastructure you would consider deploying to support this model, and produce a diagram for it.

Diagram or define a build and release pipeline for applications and/or infrastructure which would also support this platform.

**NOTE:** You may walk through detail verbally during your technical interview, rather than exhaustively detailing on a given diagram.

### Cloud Provider and Specific Technologies

You may select any given cloud provider from [GCP, AWS, Azure] and any relevant technology stack, but do be prepared to justify yourself.

You may use either a specific language or psuedo-code as you feel appropriate.

You may use publically available modules where justified, but any third party tools or templates must be MIT-licensed.

## Scenario

Each level of seniority will add additional requirements onto a prospective solution. These additional requirements are not the delta between levels inside Ensono Digital, but gives an indication of the kind of scope and scale required at each.

A client is migrating to a greenfield cloud-native platform requires a design for a hosting a simple micro-service based CMS with a non-relational back-end.

### Consultant

Consider the folowing criteria for your design:

1. Resilience and Redundancy
2. Cost efficiency

### Senior Consultant

Consider the folowing criteria for your design:

3. Multiple teams operating independently on the platform
4. Alerting, Logging and Monitoring
5. Testing of non-functional requirements

### Lead Consultant

Consider the folowing criteria for your design:

6. A secure multi-tenancy model
7. Infrastructure testing
8. Defining example NFRs for this platform.
