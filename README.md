# servas.ai Scoop bucket

Scoop manifests for the servas.ai command-line tools (Windows x64).

```powershell
scoop bucket add servas https://github.com/servas-ai/scoop-bucket
scoop install servas/bcli
```

| App | What | Docs |
|---|---|---|
| `bcli` | CLI for servas.ai Browser as a Service: real, headed cloud browsers for agents and tests over CDP | [servas-ai/bcli-public](https://github.com/servas-ai/bcli-public) |

Upgrade with `scoop update bcli`, remove with `scoop uninstall bcli`. Use a normal (non-elevated) terminal.

The manifests download the release binaries from the public release repositories and check them against the
SHA-256 values from each release's Ed25519-signed `SHA256SUMS`. The binaries are proprietary software by servas.ai;
see the license in the release repository.
