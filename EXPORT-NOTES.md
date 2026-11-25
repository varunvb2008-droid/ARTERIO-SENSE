# ArterioSense source export

This archive contains the complete current project source, configuration, tests, data samples, asset pointers, and dependency lockfile. Installed dependencies, generated build output, repository metadata, and environment secrets are excluded.

## Run locally

1. Install Bun.
2. Run `bun install` inside this folder.
3. Configure your environment variables privately for the connected backend and Lovable AI gateway. The original `.env` is deliberately not included.
4. Run `bun run dev`.

Image files are represented by the project's `.asset.json` pointers, which refer to hosted media. AI features require gateway access and backend configuration; the ZIP does not include credentials or a live database export.

## Current status

This is an export of the project as it currently stands, not a verified release. The AI assistant page is unfinished and previously reported setup/type errors have not been fixed as part of this export request.
