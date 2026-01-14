# bazel_python_override_example

Demonstrates using a Python version override with `rules_python`.

In this case, we are using `3.9.25`, which is not available with `rules_python` version `1.7.0`.

```bash
bazel run //app
```
