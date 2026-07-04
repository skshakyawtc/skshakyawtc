---
name: @skshakyawtc-coding-skill
description: "GitHub profile skill from @skshakyawtc. Use it when the task would benefit from mimicking this developer's repo choices, coding style, and implementation techniques."
---

## What they tend to build
- There isn’t enough public signal here to confidently describe a recurring product type.
- The profile has no README and no repository excerpts, so assume the work may span whatever the visible repos show rather than a single obvious niche.
- Before mirroring any “style,” inspect the actual code and commit history of the target repo.

## Coding patterns to mirror
- Prefer evidence over assumptions: derive naming, structure, abstraction level, and error-handling style from the repo itself.
- Match the repository’s existing granularity:
  - if functions are small and explicit, keep changes small and explicit;
  - if modules are layered and abstracted, don’t flatten them.
- Reuse the project’s existing conventions for:
  - file organization
  - import ordering
  - naming of components/functions/variables
  - test placement and test naming
- When signals are weak, make the smallest coherent change that fits the surrounding code.

## Product and UI taste
- No UI/product taste can be inferred from the available profile material.
- If the repo is user-facing, inspect:
  - component spacing and density
  - copy tone
  - use of icons, borders, and whitespace
  - whether the UI favors minimalism or feature visibility
- Don’t introduce a new visual style unless the repo clearly supports it.

## Tech stack clues
- No stack is visible from the provided profile data.
- Treat language, framework, and tooling as unknown until confirmed in repository files like:
  - `package.json`, `pyproject.toml`, `Cargo.toml`, `pom.xml`, `go.mod`
  - framework entry points and config files
- Use the repo’s existing tooling, formatter, and test runner rather than guessing.

## When to inspect repos first
- Always inspect first when the profile has:
  - no README
  - no pinned repo details
  - no repository excerpts
  - no obvious stack or product clues
- Inspect the target repo before coding if you need to match:
  - architecture
  - naming conventions
  - UI tone
  - error-handling behavior
  - test style
- If you can’t inspect, keep changes generic, conservative, and easy to align later.

## Repo Map


## How To Use This Skill

- Reach for this skill when the user asks for Sushil Shakya's style, when the repo stack matches this person's ecosystem, or when studying their real code would reduce made-up output.
- Pick one or more relevant repositories from the list above based on the current task.
- Clone the most relevant repository or repositories into `/tmp` for temporary inspection.
- Study the implementation details, naming patterns, architecture, UI taste, and tooling choices there.
- Return to the main task and apply the useful patterns you observed instead of copying blindly.
- Treat the upstream repositories as reference material for style and technique, then adapt them to the current codebase responsibly.
