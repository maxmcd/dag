# DAG

This is a copy of the [dag library used in terraform](https://pkg.go.dev/github.com/hashicorp/terraform/dag).

This project removes the library from terraform for easier use and replaces all uses of `tfdiags.Diagnostics` with `[]error`.
