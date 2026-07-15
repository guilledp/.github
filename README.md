# .github
My GitHub config ⭐

## Auto-merge protection

This repository includes a workflow that listens for `auto_merge_enabled` events.
If the actor enabling auto-merge is not `guilledp`, `github-copilot[bot]`, or `copilot-swe-agent[bot]`, the workflow disables auto-merge on that pull request.
