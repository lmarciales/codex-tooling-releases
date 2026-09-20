# Portable Tooling Pilot

A minimal public Codex desktop plugin distribution test. Version 0.2.0 contains one instruction-only skill with synthetic content. It has no scripts, hooks, external dependencies, connector configuration, credentials, or runtime state.

Verify repository access and file integrity before installing. Use a verified fixed revision, not a moving branch. Keep the prior verified snapshot for an explicit rollback test.

The repository contains a local marketplace catalog at `.agents/plugins/marketplace.json`. Its source path resolves from the repository root. The plugin is at `plugins/portable-tooling-check`.

A later fresh-task skill invocation should return the release identifier and the marker BLUE. That response alone does not prove installed-file integrity.

This public repository contains selected distribution files only. Access does not require a personal GitHub sign-in on the consuming laptop. Keep existing GitHub credentials and commit-signing configuration. Network policy, connector repository selection, and client configuration can still affect reads; record the actual method and failure without switching accounts or creating credentials.

Static manifest and skill validation passed on Linux. Version 0.1.0 was successfully installed from a local snapshot and invoked in a fresh desktop task in a separate environment, with installed-file integrity verified. Version 0.2.0 installation, update, rollback, and Windows remain untested.
