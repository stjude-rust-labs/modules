## Description

<!-- Describe the change this pull request makes. For new modules, briefly
explain what the module does and what tool(s) it wraps. For updates, describe
what changed and why. -->

## Tools referenced

<!-- List every external tool this module invokes. If this is a version bump,
re-confirm the license even if it has not changed. Modules that reference tools
with an unknown license will not be accepted.

  Tool          — The tool's name, linked to its homepage or repository.
  Version       — The exact version your module references, in backticks.
  License       — The full license name (e.g. MIT License, Apache License 2.0).
  SPDX          — The SPDX identifier for the license, in backticks (e.g. `MIT`).
  License file  — A direct link to the LICENSE file in the tool's repository.
  Needs review? — Mark [X] if the license is not on the approved list and
                  requires maintainer evaluation before this PR can be merged. -->

| Tool                                           | Version | License     | SPDX identifier | License file                                                  | Needs review? |
| ---------------------------------------------- | ------- | ----------- | --------------- | ------------------------------------------------------------- | ------------- |
| [ExampleTool](https://github.com/example/tool) | `1.2.3` | MIT License | `MIT`           | [Link](https://github.com/example/tool/blob/main/LICENSE)     | [X]           |
|                                                |         |             |                 |                                                               |               |

## Checklist

<!-- Pull requests will not be reviewed until every item is checked. If an item
does not apply to your contribution, check it off to acknowledge that you have
read and considered it. -->

- [ ] My contribution contains only original workflow logic. It does not include
  third-party source code, binaries, container images, or copied third-party
  scripts or similar materials.
- [ ] I have identified every external tool my module invokes and listed its
  license in the table above.
- [ ] Every tool listed uses a license from the
  [approved list](../README.md#approved-licenses), or I have flagged it for
  review in the table above.
- [ ] No tool uses a license from the
  [prohibited list](../README.md#prohibited-licenses) or any other license that
  imposes obligations triggered by network interaction, SaaS deployment, or
  similar use-based mechanisms.
- [ ] If this is a version bump, I have re-verified that the tool's license has
  not changed in a way that is incompatible with this repository's policies.
- [ ] I have the right to license my contribution under the terms of this
  repository (MIT or Apache-2.0).

## Maintainer checklist

<!-- To be completed by a maintainer before merging. If you are the pull request
author and not an independent maintainer reviewing this PR, leave these
unchecked. -->

- [ ] I have verified that every tool listed in the tools table carries a
  license from the [approved list](../README.md#approved-licenses), or have
  reviewed and approved any license flagged for review.
- [ ] No tool uses a license from the
  [prohibited list](../README.md#prohibited-licenses) or any other license that
  imposes obligations triggered by network interaction, SaaS deployment, or
  similar use-based mechanisms.
