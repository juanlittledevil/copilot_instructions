> **NOTE:**  
> This file is for project-specific overrides.  
> Unless explicitly stated below, all rules and preferences from  
> [`Copilot_INSTRUCTIONS.md`](https://github.com/juanlittledevil/copilot_instructions/blob/main/Copilot_INSTRUCTIONS.md)  
> apply to this project!

# Copilot Project Instructions Template

## Overview
- **Project Name:** [Your project name]
- **Primary Goals:** [Brief description of what this repo should achieve]
- **Primary Languages:** [C++, Python, etc.]

---

## Directory Scanning Rules

- **Include (for code search, linting, and Copilot context):**  
  - `/include/`  
  - `/src/`  
  - `/tests/`  

- **Exclude:**  
  - `/docs/`  
  - `/build/`  

---

## Coding & Workflow Overrides

- [List any overrides to global instructions, e.g., indentation, naming, special design patterns, etc.]

---

## Testing

- **Testing Framework:** [e.g., Google Test, Pytest, etc.]
- **Testing Location:** [e.g., `/tests/` directory]
- **Coverage Goals:** [Optional: % coverage, critical components, etc.]

---

## Error Handling

- [State specific error handling for this project if different from global, e.g., debug prints, exceptions, custom error objects, etc.]

---

## Security

- [Any specific security requirements or considerations for this project]

---

## Documentation

- [Specify documentation standards, file locations for docs, Doxygen configs, etc.]

---

## Planning and Session Workflow

- **Project Plan:**  
  - Located at `/Planning/PROJECT_PLAN.md`.
  - Contains overall project goals, milestones, and planning details.

- **Architecture:**  
  - Located at `/Planning/ARCHITECTURE.md`.
  - Includes architecture documentation, diagrams, and major design decisions.

- **Session Plans:**  
  - Each session should have its own file: `/Planning/SESSION_PLAN_<name>.md` (name can be a date or topic).
  - Use symlinks: `/Planning/ACTIVE_SESSION.md` should always point to the currently active session plan.
  - After a session is completed, move its plan to `/Planning/CompletedSessions/`.

- **ACTIVE_SESSION.md usage:**  
  - Always use `/Planning/ACTIVE_SESSION.md` to refer to the session currently in progress, regardless of its actual filename.
  - This ensures automation and configuration always work with the active session.

---

## Additional Notes

- [Any other project-specific info Copilot should know]

---

> **Instructions here override the global `Copilot_INSTRUCTIONS.md` settings only if explicitly stated.**