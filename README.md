# Infrastructure Live

This repository contains all live Infrastructure As Code for qa, stage and prod environment. It's based on [Terraform][1], and leverage [Terragrunt][2] to help DRY code.

---

## Dev environment setup on Mac

### 1. Install dependencies

* [`Terraform`][1]
* [`Terragrunt`][2]
* [`pre-commit`](https://pre-commit.com/#install)
* [`terraform-docs`](https://github.com/segmentio/terraform-docs) required for `terraform_docs` hooks.
* [`TFLint`](https://github.com/terraform-linters/tflint) required for `terraform_tflint` hook.

##### MacOS

```bash
brew install terraform terragrunt pre-commit gawk terraform-docs tflint
```

---
[1]: https://www.terraform.io/
[2]: https://terragrunt.gruntwork.io/
