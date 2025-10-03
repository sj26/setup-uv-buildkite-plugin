# Setup uv

Installs [`uv`](https://github.com/astral-sh/uv) for use in [Buildkite](https://buildkite.com) builds.

## Example

```yaml
steps:
- name: pytest
  plugins:
  - sj26/setup-uv
  command: uv run pytest
```
