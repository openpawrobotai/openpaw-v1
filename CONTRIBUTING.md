# Contributing to Orbie

Contributions are welcome. One thing to read first.

## The contributor licence agreement

Before a contribution can be merged, you need to agree to the
[Contributor Licence Agreement](CLA.md).

**You keep the copyright in your work.** Nothing is assigned. What the agreement
grants is a licence broad enough that AYVA LABS LIMITED can relicense
contributions, including under proprietary terms.

That last part is stated plainly because it should be. This project publishes an
open reference design under CERN-OHL-S-2.0. Ayva Labs also builds a commercial
robot, and the designs for that one are not published. A contribution you make
here may end up in that product. If you are not comfortable with that, please do
not contribute, and no hard feelings. The agreement says the same thing in
section 3.

### How to agree

Tick the acknowledgement in the pull request template. That covers that
contribution and every later one.

For substantial hardware contributions, or if you are contributing on behalf of
a company, a signed copy is required instead. Write to legal@ayvalabs.com.

## What is licensed how

| Material | Licence |
|---|---|
| Firmware, application code, tooling | Apache-2.0 |
| Mechanical CAD, PCB layouts, industrial design | CERN-OHL-S-2.0 |
| Documentation, photography, video | CC BY-SA 4.0 |

Contributions to `Mechanical/`, `Electrical/` and `Design/` carry the reciprocal
licence and receive the closest review, since those are the files the commercial
design relates to.

## Practical notes

- Open an issue before a large change, so nobody builds something that will not
  be merged.
- Hardware changes need the source files, not only exports. KiCad projects, not
  gerbers alone. CAD sources, not only STLs.
- Say what you tested on. "Builds" and "ran on an actual robot" are different
  claims and both are useful.
- Third party material must be identified with its source and licence, per
  section 6 of the CLA.
