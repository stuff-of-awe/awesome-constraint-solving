<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome Constraint solving and optimisation

Constraint programming, integer/linear programming and solver-independent modelling. Feasible assignments, optimum bounds and optimality certificates carry different guarantees.

**Status:** starter collection, 2026-11-15. Curator: unassigned. These are independently written short annotations of external resources; no benchmark, integration, solver invocation or checker execution has been performed for this starter.

## Learn and get started

- [MiniZinc](https://www.minizinc.org/) — Solver-independent constraint modeling and FlatZinc compilation.
- [MiniZinc handbook](https://docs.minizinc.dev/en/stable/) — Structured tutorial, modeling patterns, and backend configuration.
- [SCIP](https://scipopt.org/) — Constraint integer programming and exact/approximate solver distinctions.

## References and implementations

- [GNU GLPK](https://www.gnu.org/software/glpk/) — Open linear and mixed-integer programming library.
- [OR-Tools](https://developers.google.com/optimization/) — CP-SAT and optimization modeling from Google.
- [HiGHS](https://highs.dev/) — High-performance linear, mixed integer and quadratic optimization.

## Benchmark, examples and community paths

- [Gecode](https://github.com/Gecode/gecode) — Constraint programming toolkit and modeling examples.
- [JuMP](https://jump.dev/) — Julia optimization modeling interface and solver compatibility layer.

## First exercise — not executed here

Write a small scheduling model in MiniZinc and solve with two backends; preserve solver configuration, objective, bound and proof/termination status.

## Evidence and interoperability

A solver reporting a feasible solution has not necessarily proved optimality. Compare supported constraints, numerical tolerance, integrality, backend termination and reproducible receipts.

Capture provenance (source commit, tool and checker versions, flags, inputs, assumptions, certificate formats, output status, elapsed time, licence) before using an entry in a research/assurance claim.

## Upstream survey, curation and contribution

A preliminary survey on 2026-11-15 compared broader resources such as [awesome-formal-verification](https://github.com/hohieuai/awesome-formal-verification), [formal-verification-resources](https://github.com/astrio-labs/formal-verification-resources), plus canonical projects above. This is not an exhaustive survey and no external descriptions were imported. The focused value here is evidence-aware navigation and links from the [ECHIDNA coverage ledger](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/CATALOGUE.adoc). Inclusion is not an endorsement, and upstream materials retain their respective licences.

Contribute fixes and additional learning material through an [issue](https://github.com/stuff-of-awe/awesome-constraint-solving/issues) or [PR](https://github.com/stuff-of-awe/awesome-constraint-solving/pulls); see [maintenance policy](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc). Original annotations are CC-BY-SA-4.0. Collectors and maintainers are invited; quarterly review is a goal, not evidence of actual review.
