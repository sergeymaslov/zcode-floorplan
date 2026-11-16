# Changelog

## 0.2.0

- Ask bar answers through the **ZCode CLI** (`zcode --prompt` in its read-only plan mode), with
  follow-up questions resuming the session (`--resume`). Search order: ZCode → Claude Code → Codex.
- The map page names and labels the ZCode agent (chip, warnings, sign-in hints).
- `open.mjs` passes `--zcode <path>` through to the map server.

## 0.1.0

- Initial ZCode packaging of [haydenschmitty/floorplan](https://github.com/haydenschmitty/floorplan)
  v0.8.0 (MIT).
- `SKILL.md` adapted: `${ZCODE_PLUGIN_ROOT}` paths, maps built with `--agent none`, Claude-specific
  bits (CLAUDE.local.md notes, "Fix with Claude" prompts) dropped.
