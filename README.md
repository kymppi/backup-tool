# backup-tool

This is a TUI/CLI for restic adding a lot of features

## Folder Structure

```
/
├── cmd/
│   ├── daemon/
│   ├── tui/
├── internal/
│   ├── daemon/
│   ├── tui/
├── pkg/
│   ├── config/
│   ├── restic/
├── ui/
│   ├── views/
├── scripts/
```

`/cmd/` contains the entrypoints for the different binaries

`/internal/` contains the internal packages

`/pkg/` contains the shared packages

`/ui/` contains the UI related files

`/scripts/` contains the scripts that are used for building and testing
