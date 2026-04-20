---
name: test-skill
description: Use when the user explicitly asks to test whether skills from the Orbit config repo are installed or triggering correctly.
---

# Test Skill

Use this skill only when the user explicitly mentions `test-skill` or asks to verify that Orbit-managed skills are available.

When triggered:

1. State that `test-skill` is active.
2. If the user asks for a sample response, return `orbit-config skill test passed`.
3. Keep the response short and avoid unrelated tool calls.
