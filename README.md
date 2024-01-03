# deno-workspace-playground

Testing denos `--unstable-workspaces` to create a workspace with multiple deno
projects.

## Usage

```sh
# Run API
deno run -A --unstable-workspaces src/api/main.ts

# Run App
deno run -A --unstable-workspaces src/app/main.ts

# Run Checks
deno check --unstable-workspaces **/*.ts
```
