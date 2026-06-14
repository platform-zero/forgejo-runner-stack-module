# forgejo-runner stack module

- Module id: `forgejo-runner`
- Module repo: `forgejo-runner-stack-module`
- Source repo: none declared
- Lifecycle: `active`

## Owned overlays
- `stack.compose/forgejo-runner.yml`
- `stack.config/forgejo-runner`
- `stack.containers/forgejo-runner`

## Dependencies
- `forgejo`
- `stack-foundation`

## Validation

```sh
./tests/validate.sh
```

## Lifecycle

`active` modules are expected to keep `stack.module.json`, owned overlays, and `tests/validate.sh` in sync.
