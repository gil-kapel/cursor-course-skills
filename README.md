# cursor-course-2026 — Agent Skills

Agent skills for the **cursor-course-2026** Hebrew Cursor course.

Each skill is a self-contained folder with a `SKILL.md` (the agent workflow), optional `assets/`, `references/`, and `scripts/`.

## Structure

```
module-02-skills-and-agents/
  lesson-2.1-skills-agents-asm/
    cursor-skill-foundation/        # Meta-skill: create & improve skills
  lesson-2.2-product-agent-prd/
    product-prd-agent/              # PRD generation agent
  lesson-2.3-tech-lead-architecture/
    tech-lead-architecture-agent/   # Architecture design agent
  lesson-2.4-ux-user-flow/
    ux-user-flow-agent/             # UX user flow agent
  lesson-2.5-ui-design-systems/
    ui-design-systems-agent/        # UI design systems agent
  lesson-2.6-security-agent/
    security-review-agent/          # Security review agent
  lesson-2.9-dev-agent-composer/
    dev-composer-agent/             # Dev composer agent
  lesson-2.10-quality-gate-agent/
    quality-gate-agent/             # Quality gate agent
  lesson-2.11-debug-agent/
    debug-fix-agent/                # Debug & fix agent
```

## Install a skill via ASM

```bash
asm add skill github:gil-kapel/cursor-course-skills/module-02-skills-and-agents/lesson-2.2-product-agent-prd/product-prd-agent
```

Or install all skills for a lesson using sparse checkout (see `bundle_module02_skills.py` in the main course repo).

The canonical public paths now match the course repo lesson numbering (`2.9`, `2.10`, `2.11`). Older `2.7`, `2.8`, and `2.9` folders are kept only as legacy copies where still present.

## Course repo

Main course: [cursor_course](https://github.com/yairbarak22/acada_me)
