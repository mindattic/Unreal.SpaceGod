---
codex: 1
project: Unreal.SpaceGod
code: USG
layer: stories
status: living
updated: 2026-11-05
---
<!-- GENERATED from MindAttic.Tickets/data/Tickets.db by `tickets db render`. Do not edit: this file is rewritten from the database; change stories and tickets with the tickets CLI. -->

# Unreal.SpaceGod — User Stories
> ✅ done (shipped & tested) · 🟡 partial · ⬜ planned. Every ✅ cites the test.

## Priority backlog
_Nothing recorded yet._

## Tickets
> Permanent log of every change and fix — this repo's ticket system. Rows are append-only: never
> delete or reword one; only move its Status (open → closed / wont-do) and fill in Ref. Status is
> a word, not a glyph, so tickets don't count toward the story index. Keep this section last.

| ID | Date | Type | Status | Summary | Ref |
|---|---|---|---|---|---|
| USG-T1 | 2026-11-05 | docs | closed | Start the permanent ticket log in the ticket database | — |
| USG-T2 | 2026-11-06 | feature | closed | Adopt the shared off-by-default --headless launch mode (Unreal.Shared) | — |
| USG-T3 | 2026-11-10 | chore | closed | Mirror the fleet-wide .agent/ portable command catalog into this repo and regenerate docs/USER_STORIES.md (catches it up to the US -> USG ticket-code rename already in the ticket database) | — |
| USG-T4 | 2026-11-10 | chore | closed | CSharp/.gitignore did not exclude the whole UnrealSharp-generated Script/UnrealSpaceGodCSharp.RuntimeGlue/ project (only its bin/obj/launchSettings.json); a build left the generated AssetIds.cs/AssetTypes.cs/GameplayTags.cs/TraceChannel.cs/.csproj as untracked source. Ignore the whole directory, matching Unreal.Playground's CSharp/.gitignore precedent (Script/UnrealSoulslikeCSharp.Glue/) | — |
| USG-T5 | 2026-11-10 | chore | closed | Commit Cpp/Config/DefaultInput.ini found uncommitted after a crashed session: stock UE5 InputSettings defaults (EnhancedInput/VR/gamepad axis config written by the editor), no custom bindings, well-formed and complete; verified against the tracked DefaultEngine.ini/DefaultGame.ini convention | — |
