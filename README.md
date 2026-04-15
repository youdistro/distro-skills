# distro-skills

Pre-made skills for [Distro](https://distro.dev) — the AI content agent for founders and marketers.

Skills teach Distro domain expertise so it can create better, platform-native content. Instead of generic AI output, skills give Distro real knowledge about character limits, algorithm signals, formatting rules, engagement patterns, and proven content frameworks.

## Available Skills

| Skill | Category | Description |
|-------|----------|-------------|
| [LinkedIn Posts](skills/linkedin-posts) | Platform | Write scroll-stopping LinkedIn posts with algorithm-aligned hooks, formatting, and engagement strategies |
| [Twitter/X Threads](skills/twitter-threads) | Platform | Craft viral X threads with scroll-stopping lead tweets, strong transitions, and engagement tactics |
| [Content Repurposing](skills/content-repurposing) | Strategy | Transform one long-form piece into 8-12 platform-native derivatives |
| [Thought Leadership](skills/thought-leadership) | Strategy | Develop original perspectives, contrarian takes, and opinion-driven content |
| [Newsletter Writing](skills/newsletter-writing) | Writing | Write newsletters that get opened, read, and clicked — with data-backed strategies |
| [Competitor Analysis](skills/competitor-analysis) | Strategy | Analyze competitor content strategies and turn findings into content angles |
| [Personal Brand for Founders](skills/personal-brand-founder) | Founder | Build a founder personal brand with build-in-public storytelling |

## How to Use

Browse and add skills through the **Skills Library** in the Distro app. Skills are automatically loaded when relevant to your content task.

## Skill Format

Each skill lives in its own directory under `skills/` and contains:

```
skills/
  skill-name/
    SKILL.md         # The skill content (YAML frontmatter + markdown)
    metadata.json    # Display metadata, category, tags, version
```

### SKILL.md Structure

```markdown
---
name: skill-name
description: One-line description that helps the agent know when to load this skill.
---

# Skill Title

## Overview
What this skill teaches and when to use it.

## Best Practices
The core domain expertise — specific, actionable, and current.

## Structure Templates
Concrete templates and frameworks.

## Quality Checklist
What to verify before delivering content.
```

### metadata.json Structure

```json
{
  "name": "skill-name",
  "displayName": "Display Name",
  "description": "What this skill does for the user.",
  "category": "platform|strategy|writing|founder",
  "tags": ["relevant", "tags"],
  "author": "Distro",
  "version": "1.0.0"
}
```

## Categories

| Category | Label | Description |
|----------|-------|-------------|
| `platform` | Platform-Specific | Write for specific platforms with native formatting |
| `strategy` | Content Strategy | Plan, analyze, and optimize your content approach |
| `writing` | Writing | Master specific content formats and writing styles |
| `founder` | Founder | Build your personal brand as a startup founder |

## Contributing

Community contributions are coming soon. If you'd like to submit a skill, stay tuned for contribution guidelines.

## License

MIT
