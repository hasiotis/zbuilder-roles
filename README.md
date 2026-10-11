# zbuilder-roles

Ansible roles used by ZBuilder to provision Debian/Ubuntu hosts.

- `common` – base system setup: sudo, packages, locale, timezone, motd, vimrc
- `hardening` – SSH hardening, fail2ban, optional unattended upgrades
- `docker-daemon` – Docker CE from the upstream apt repo, daemon config, daily prune
- `golang` – Go SDK from the official tarball
- `python` – Python tooling (uv, uvx, ruff) from the Astral GitHub releases
- `aws-cli` – AWS CLI v2 via the official installer
- `utils` – standalone CLI binaries (kubectl, helm, stern, k9s, kind, sofka, devspace)
- `claude-code` – Claude Code CLI via the official native installer, per user
