# A fork of https://github.com/mensonen/diameter
with no intention of merging it back to master.

## Changes
- removed every feature added after python3.6
  - `from __future__ import annotations` (3.7)
  - some type annotations, like `list[...]` instead of `List[...]`, `A | B` instead of `Union[A, B]` (3.8, 3.9)
  - narval operator `:=` (3.8)
  - match (3.10)
