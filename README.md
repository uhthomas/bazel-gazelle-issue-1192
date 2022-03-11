# Bazel Gazelle #1192

Try to build goose:

```sh
bazel build @com_github_pressly_goose_v3//...
```

and be met with:

```
compilepkg: /home/thomas/.cache/bazel/_bazel_thomas/b57cca483c8e5e6ea6286570e14f5568/sandbox/linux-sandbox/223/execroot/__main__/external/com_github_pressly_goose_v3/goose_test.go:158:12: could not embed examples/sql-migrations/*.sql: no matching files found
FAILED: Build did NOT complete successfully
```
