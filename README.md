# Tracee Docker GitHub Action

This GitHub Action runs Aqua Security's Tracee using Docker.
Logs will be stored in tracee.log file
## Usage

```yaml
uses: pushkarpawar15/tracee-docker-action@v1
with:
  NOTIFY_URL: ${{ NOTIFY_URL }}
  NOTIFY_TOKEN: ${{ NOTIFY_TOKEN }}
