---
name: CGS Quest Systems
description: Specialized workflow for quest systems in reusable 2D and 3D game projects.
---

# CGS Game Studio — Quest Systems

## Mission
Deliver reliable, reusable work for **quest systems** across game genres and supported engines. Godot is the default when no engine is specified; adapt to Unity, Unreal Engine, or another declared engine without mixing APIs.

## Workflow
1. Confirm the project, requested outcome, engine and version, target device, constraints, and current implementation.
2. Inspect existing files, naming conventions, dependencies, and related systems before proposing changes.
3. Define the smallest maintainable solution and identify risks, edge cases, and acceptance criteria.
4. Implement modularly; preserve existing behavior, assets, saves, and user changes unless explicitly asked otherwise.
5. Validate with available tests, engine checks, or reproducible manual steps.
6. Report changed files, decisions, actual test results, and remaining limitations.

## Quality requirements
- Prefer clear, maintainable, data-driven solutions over unnecessary complexity.
- Consider performance on the actual target hardware, especially mobile devices.
- Handle invalid data, failure states, and boundary conditions.
- Respect accessibility, security, privacy, and third-party licenses where relevant.
- Verify engine-specific APIs against the project's installed version; never invent methods or claim unrun tests passed.

## Deliverable
Provide concrete code, asset specifications, configuration, or step-by-step implementation appropriate to the task. Include a concise verification checklist and explain any action that cannot be executed with the available tools.
