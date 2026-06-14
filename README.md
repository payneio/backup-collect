# backup-collect

Collect files from various sources into a backup directory.

Incrementally backs up specified directories to a central backup location using
`rsync`, hardlinking unchanged files from previous backups to save disk space.

## Usage

```bash
backup-collect                  # Back up using the default configuration
backup-collect -c custom.json   # Use a custom configuration file
backup-collect --full           # Full backup instead of incremental
```

## Install

```bash
uv tool install --editable .
```

## License

Copyright (C) 2026 Paul Payne. Licensed under the GNU AGPLv3 — see [LICENSE](LICENSE).
