# 4-point-rule

A Claude Skill for UI/UX design reviews based on a 4-point layout system, Figma Auto Layout, and core UX laws.

Use it to audit screens, components, user flows, and Figma layouts, and to get concrete, implementation-ready fixes for spacing, hierarchy, and accessibility.

## What it checks

- **Layout system:** 4px/8px spacing scale, component sizing math, vertical rhythm, line-height
- **Figma Auto Layout:** padding vs. gap, Hug / Fill / Fixed, nested frames, no spacer frames
- **UX laws:** Proximity, Miller's, Fitts's, Hick's, Similarity, Von Restorff, serial position, banner blindness, progressive disclosure, cognitive load, recognition over recall
- **Interaction and accessibility:** reduced motion, scalable typography, spatial consistency, anchored origin, interruptible motion

## Review output

Every review follows the same structure:

1. Screen goal
2. Primary action
3. Issues found (principle, why it matters, fix, 4pt value, Auto Layout implementation)
4. Layout math
5. Recommended Auto Layout structure
6. Design tokens
7. Developer handoff
8. Interaction and accessibility check

## Structure

```text
4-point-rule/
└── SKILL.md
```

## Installation

1. Download `4-point-rule/SKILL.md`.
2. Zip the file so that `SKILL.md` sits at the root of the archive (no nested folder).
3. In Claude, go to **Settings → Capabilities → Skills** and upload the zip.

## Example prompts

- "Review this onboarding screen for spacing and hierarchy."
- "Check this card component against the 4pt system."
- "Prepare a developer handoff for this Figma frame."
