---
name: bolter-tones
description: >
  Reference library of Bolt.new team member voice and tone profiles.
  Use when writing social content in a specific person's voice, matching
  their posting style, or comparing tones across the Bolt team.
  Each profile covers: core traits, sentence patterns, emoji usage,
  posting mix, tone spectrum, and key differences from other voices.
user-invokable: false
metadata:
  version: 1.1.0
---

# Skill: Bolter-Tones

**Goal:** Provide structured voice and tone reference profiles for Bolt.new team members to ensure consistent, authentic ghostwriting and content creation.

## Available Voices

| Person | Role | Handle | Menu blurb | File |
|---|---|---|---|---|
| Eric Simons | CEO | @EricSimons | Builder-CEO energy, casually confident, technically fluent | `references/eric-simons-tone.md` |
| Alexander Berger | COO | @alexberger_me | Operator-commentator energy, internet-native, humor as the hook | `references/alexander-berger-tone.md` |
| Dominic Elm | Engineering | @elmd_ | Engineer-educator energy, curiosity-driven, technically deep | `references/dominic-elm-tone.md` |
| Garrett Serviss | Marketing | @GarrettServ | Marketing-operator energy, structured, benefit-led, polished but warm | `references/garrett-serviss-tone.md` |
| Donald Savard | PMM (inkko) | @inkko44 | Launch-mode PMM energy, punchy, vibes-driven, always shipping | `references/donald-savard-tone.md` |
| Gary Ballabio | VP Partnerships | @ballabio | Enterprise partnerships energy, polished, hashtag-forward, amplifier-first | `references/gary-ballabio-tone.md` |

This table is the **single source of truth for the voice roster**. write-strike builds its voice-selection menu from it at draft time (Bolt.new TOV default + these rows via their Menu blurbs + Ogilvy). **Adding a voice:** drop a profile file in `references/`, add a row here with a short Menu blurb; write-strike's menu follows automatically, no edit there.

## How to Use
1. Read the relevant person's tone file before drafting content in their voice.
2. Match their sentence patterns, emoji style, and topic framing.
3. Avoid anything listed in their "What He Avoids" section.
4. Use the "Key Differences" section to ensure you're not blending voices.
