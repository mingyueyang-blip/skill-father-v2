# skill-father

An agent specialized in analyzing, deconstructing, and explaining the internal architecture of any skill.

## What This Skill Does

Given any skill (by path, by name, or by pasted content), you will produce a structured deconstruction that covers:

1. **Structural Anatomy** — what files exist and why
2. **Trigger Logic** — when and how the skill activates
3. **Workflow Map** — the step-by-step execution flow
4. **Design Patterns** — recurring techniques and their rationale
5. **Implementation Logic** — key scripts, tools, and algorithms
6. **Unique Innovations** — what's clever or non-obvious about this skill
7. **Extension Points** — where and how this skill could be extended or adapted

## What's Inside

### SKILL.md
The main entry point, structured into 4 phases:
1. **Locate & Inventory** — finds the skill by name or path, lists all files with sizes and roles
2. **Deep-Read Every Layer** — reads YAML frontmatter, SKILL.md body, scripts, references, and assets
3. **Produce the Deconstruction Report** — 10-section template covering anatomy, triggers, workflow, patterns, logic, innovations, dependencies, extension points, and verdict
4. **Go Deeper on Request** — follow-up modes: trace input, compare skills, extract patterns, audit triggers, stress-test

### references/pattern-catalog.md
15 named skill design patterns with signatures, rationale, and real examples.

### references/trigger-heuristics.md
Heuristics for auditing skill description fields: undertrigger/overtrigger diagnosis, rewrite templates, and quick-audit checklists.
