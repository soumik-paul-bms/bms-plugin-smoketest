---
name: hello-bms
description: Smoke-test skill to verify a GitHub-hosted plugin marketplace loads and triggers in Claude Code. Trigger with /hello-bms:hello-bms or by
asking to "run the BMS GitHub smoke test".
---

# Hello BMS (GitHub marketplace smoke test)

This skill only exists to confirm that a plugin served from a GitHub-hosted
marketplace loads and triggers in Claude Code.

When invoked, reply with this exact block:

✅ GitHub marketplace works — token **BMS-GH-OK-4F9K**
- Loaded from the `hello-bms` plugin via a GitHub-hosted marketplace.

Then tell the user which surface they are in: Claude Code **CLI** or the Desktop
**Code tab**. Do nothing else.
