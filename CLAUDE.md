# Claude Project Instructions

## Skill Auto-Invocation Rules

When working in this project, automatically invoke the appropriate skill based on the task context. Do not wait for the user to request a skill - proactively use them when the trigger conditions are met.

### Available Skills & Triggers

| Skill | Invoke When |
|-------|-------------|
| `ux-laws` | Reviewing designs, analyzing UI/UX, evaluating interfaces, choosing between design alternatives, designing forms/navigation/checkout/dashboards, or any usability discussion |
| `creative-director` | Brand-related decisions, visual identity work, ensuring brand consistency |
| `frontend-design` | Building frontend components, HTML/CSS/JS development |
| `email-coder` | Creating HTML emails, email templates |
| `website-creator` | Building websites or landing pages |
| `marketing-copywriter` | Writing marketing copy, headlines, CTAs |

### Trigger Phrases (Examples)

**ux-laws:**
- "review this design"
- "analyze this UI"
- "check for UX issues"
- "any improvements we can make"
- "is this usable"
- "help me decide between [design options]"

**creative-director:**
- "does this match our brand"
- "brand guidelines"
- "visual identity"

**frontend-design:**
- "build this component"
- "create this page"
- "style this"

### Important

1. **Invoke skills at the start** - Don't analyze first, then consider skills. Check skill applicability immediately.
2. **Skills provide expertise** - They contain specialized knowledge and frameworks that improve response quality.
3. **Multiple skills can apply** - For complex tasks, invoke the most relevant skill first.
