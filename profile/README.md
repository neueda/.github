# Welcome to Zinkworks

Zinkworks is a software engineering and technology partner focused on delivering high-quality solutions in complex domains including telecommunications and financial services.

We work on practical engineering problems that matter in the real world: modernising platforms, accelerating delivery, improving reliability and helping clients move faster with confidence.

## What you'll find here

This GitHub is the front door to the work, thinking and reusable assets that support Zinkworks delivery.

- Engineering projects and accelerators
- Reusable delivery components
- Domain-specific solution assets
- Internal platform and product initiatives

## AgentFoundry

AgentFoundry is Zinkworks' reusability catalogue for project delivery.
Put 
Its purpose is to make proven delivery components visible and reusable so teams can start faster, reduce setup effort, improve consistency and deliver with more confidence. Over time, it helps turn delivery knowledge into reusable Zinkworks IP.

### Why it exists

- Reduce repeated setup work across projects
- Improve delivery speed and consistency
- Support better estimation and lower delivery risk
- Create a clearer catalogue of reusable project assets

### Components

| Repo | Description | When it should be used | Owners |
|---|---|---|---|
| [agentfoundry-fastapi-template](https://github.com/neueda/agentfoundry-fastapi-template) | `Production-oriented FastAPI backend template with clean architecture: routers, services, repositories, schemas, ORM models, dependency injection, and test coverage across unit, integration, and end-to-end levels. It also includes patterns for GCP services such as BigQuery and GCS.` | `Use when starting a Python backend or API and you want a maintainable, testable structure from beginning. Good for internal services, CRUD APIs, business logic services, and integration-heavy backends.` | `[Owner name]` |
| [agentfoundry-adk](https://github.com/neueda/agentfoundry-adk) | `Starter repo for building multi-agent applications with Google ADK. The current content is centered on a supervisor/router pattern, where a root agent routes requests to specialist sub-agents with separate prompts, tools, and error handling.` | ` Use when building AI agent systems where requests need to be classified and delegated across specialist agents, such as support, billing, operations, or workflow assistants. Best suited for agent orchestration and tool-driven AI workflows rather than standard web apps.` | `[Owner name]` |
| [zink-ci](https://github.com/neueda/zinkci) | Reusable CI/CD platform template for GCP, combining Terraform and Helm to provide shared platform infrastructure, pipeline definitions, build/deploy/security automation, and multi-tenant delivery patterns. See the [zinkci Usage Guide](https://github.com/neueda/zinkci/blob/main/README.md), [Architecture](https://github.com/neueda/zinkci/blob/main/ARCHITECTURE.md), and [Contributing](https://github.com/neueda/zinkci/blob/main/CONTRIBUTIONS.md) docs. | `Use when setting up or standardizing CI/CD platforms across multiple teams or projects. Best for platform-level DevOps reuse, centralized pipeline management, GitOps-style workflows, and consistent delivery infrastructure.` | `[Owner name]` |
| [nextjs](https://github.com/neueda/agentfoundry-nextjs-template) | `Standardized Next.js frontend starter with React, TypeScript, Tailwind, shadcn/ui, Zustand, TanStack Query/Table, auth scaffolding, dashboard layout, and Vitest-based test setup. It is intended to remove repeated frontend setup work.` | Use when starting a web frontend quickly, especially for authenticated internal apps, dashboards, admin portals, or business UIs where a consistent frontend foundation is useful. | `[Owner name]` |

## Get in touch

If you're exploring Zinkworks work or looking for the right team to speak to, start here and follow the relevant project or component documentation.
