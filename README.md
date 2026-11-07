# coderabbit

Central [CodeRabbit](https://coderabbit.ai) config for every `kleinbem-dev` repo.
CodeRabbit reads `.coderabbit.yaml` from this repo for any repo without its own.
While it exists, the web UI settings don't apply.

A repo that needs something extra adds its own `.coderabbit.yaml` with
`inheritance: true`, so it merges on top of this one instead of replacing it.
See [central configuration](https://docs.coderabbit.ai/configuration/central-configuration)
and [inheritance](https://docs.coderabbit.ai/configuration/configuration-inheritance).

CI checks the file against CodeRabbit's schema on every PR.

The `kleinbem` user account has its own copy in `kleinbem/coderabbit`.
Keep the two in step.
