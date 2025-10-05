# GitHub Self-Hosted Runner Playbook

Ansible playbooks to automatically install GitHub Actions self-hosted runners for an org-level deployment and manage the runner machine(s).

## Project Structure

```
.
├── inventory.ini          # Host inventory
├── vars.yaml              # Configuration variables
├── mise.toml              # Tool versions + tasks
└── playbooks/
    ├── install.yaml       # Install GitHub runner
    ├── update.yaml        # Reboot system
    ├── update.yaml        # Update system packages
    └── uninstall.yaml     # Uninstall GitHub runner
```
