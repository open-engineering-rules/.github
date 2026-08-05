# Open Engineering Rules

Reusable engineering rules for humans, AI agents, and automated engineering platforms.

Open Engineering Rules is the home of reusable engineering rules that describe how engineering should be performed.

Rules complement Open Engineering Conventions by expressing guidance, policies, validation logic, best practices, architectural principles, and quality requirements that can be consumed by both humans and machines.

The goal is to make engineering knowledge portable, versioned, composable, and executable.

⸻

## Vision

Engineering knowledge should not live only in documentation.

It should also be understandable by:

* engineers
* AI coding assistants
* CI/CD pipelines
* IDEs
* validators
* engineering platforms
* runtime environments

Open Engineering Rules provides a shared, open library of reusable rules that can be applied consistently across projects and organizations.

⸻

## Position within Open Engineering
```
Open Engineering Story
          │
          ▼
Open Engineering Plan
          │
          ▼
Open Engineering Elements
          │
          ▼
Open Engineering Capabilities
          │
          ▼
Open Engineering Rules
          │
          ├── Human Guidance
          ├── AI Instructions
          ├── Validation
          ├── Policies
          ├── Best Practices
          ├── Quality Gates
          └── Runtime Constraints
```
Rules transform engineering knowledge into reusable assets.

⸻

## What is a Rule?

A Rule describes how something should be implemented, reviewed, validated or operated.

Typical information includes:

* purpose
* rationale
* applicability
* severity
* recommendations
* examples
* references
* machine-readable metadata

Rules are technology-independent whenever possible.

⸻

## Example Rule Categories

### Architecture

* Single Responsibility
* Loose Coupling
* Composition over Duplication
* Event-Driven Design
* Stateless Components

### Documentation

* Repository Structure
* README Quality
* API Documentation
* ADR Requirements
* Traceability

### Source Code

* Naming
* Error Handling
* Logging
* Testing
* Dependency Management

### Kubernetes

* Resource Design
* Security
* Networking
* RBAC
* Scaling

### GitHub

* Repository Layout
* Pull Requests
* Releases
* Labels
* Issue Templates

### AI

* Prompt Design
* Agent Collaboration
* Tool Usage
* Memory
* Safety

### Robotics

* Capabilities
* Sensors
* Motion
* Recovery
* Diagnostics

### Picos

* Pico Design
* Event Handling
* State Management
* Security
* Testing

⸻

## Human and Machine Readable

Every rule may exist in multiple representations.
```
rules/
    pico/
        single-responsibility/
            README.md
            rule.yaml
            examples/
            tests/
    kubernetes/
    documentation/
    github/
    security/
```
This allows the same rule to be consumed by:

* engineers
* documentation generators
* AI assistants
* GitHub Actions
* validators
* IDE extensions
* engineering runtimes

⸻

## Principles

Open Engineering Rules are:

* Open
* Versioned
* Reusable
* Composable
* Technology-neutral
* AI-native
* Evidence-driven
* Community maintained

⸻

## Relationship to Open Engineering Conventions

Conventions define shared structure.

Rules define shared behaviour.

Examples:
```
Conventions	Rules
Repository layout	Repository quality requirements
Metadata schema	Metadata validation
Naming format	Naming recommendations
Version format	Release policy
API schema	API design guidance
```
Together they provide consistency across engineering ecosystems.

⸻

## Repository Structure
```
rules/
    architecture/
    documentation/
    github/
    kubernetes/
    picos/
    robotics/
    security/
    testing/
    ai/
```
Each ruleset may include:

* documentation
* examples
* validation
* machine-readable definitions
* reference implementations

⸻

## Who is this for?

Open Engineering Rules is intended for:

* software engineers
* platform engineers
* architects
* DevOps teams
* AI engineering agents
* robotics engineers
* documentation teams
* open-source communities

⸻

## Contributing

We welcome contributions from the community.

Whether you are documenting best practices, formalising architectural principles, or creating machine-readable validation rules, your contributions help make engineering more consistent, reusable, and AI-friendly.

⸻

## Open Engineering

Open Engineering is an open ecosystem for building software, systems, documentation, automation, robotics, and AI using shared engineering knowledge.

Open Engineering Rules captures that knowledge in a form that can be reused by people and machines alike.
