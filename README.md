# cantina

Shared libraries that every Kolto Labs Discord bot needs, and nothing that belongs to one product.

## Scope

- Discord client factory, logger, guild and global command deployment
- Embed builders
- Typed environment loading (the generic loader only; each bot owns its own schema)

## Not in scope

- Anything about Trask, Pazaak or HK-86
- Accounts, sessions or OAuth. Sign-in is one org-wide OpenID Connect service; bots verify tokens with a standard library.

## Consumers

`trask`, `pazaak`, `hk-86`. They depend on published versions of these packages, never on a git path.

## Status

Scaffold. Code is being migrated from `OpenKotOR/community-bots` with history, one draft pull request at a time.

Kolto Labs is an independent, non-commercial fan project, not affiliated with Lucasfilm, Disney, BioWare, Electronic Arts, Obsidian, Aspyr or Saber Interactive. This repository contains no game assets.
