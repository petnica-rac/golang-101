# golang-101

Introductory hands-on Go workshop for participants with prior programming experience but no Go background. The goal is to cover enough of the language that attendees can write useful programs independently by the end of the 6-hour session.

## What is covered

| Segment | Topic | Concepts |
|---------|-------|----------|
| 0 | Setup | VS Code, Go installation, hello world |
| 1 | Variables & control flow | Primitive types, `if`/`switch`/`for`, I/O |
| 2 | Functions, slices & maps | Function signatures, multiple return values, dynamic collections, `range` |
| 3 | Pointers & structs | Memory addresses, structs, value vs. pointer receivers, methods, the `Stringer` interface |
| 4 | Error handling | `value, err` pattern, `errors.New`, `fmt.Errorf`, custom error types |
| 5 | Modules & libraries | `go mod`, standard library, installing and using third-party packages |

Intentionally out of scope: interfaces (beyond `Stringer`), generics, testing, goroutines/concurrency.

## Format

Each segment follows the same pattern: a live-coded demo by the instructor → participants work on an assignment. A cheat sheet with the key syntax for the segment is handed out before the demo and stays available throughout.

Assignments come in a main variant (required for everyone) and a bonus variant (for participants who finish early).

## Directory structure

```
segment0/   setup guide for Windows, macOS, and Linux
segment1/   cheatsheet, demo notes, assignment (variables & control flow)
segment2/   cheatsheet, two demo notes, assignment (functions, slices, maps)
segment3/   cheatsheet, demo notes, assignment (pointers & structs)
segment4/   cheatsheet (error handling — extends the segment 3 assignment)
segment5/   cheatsheet (modules & libraries — instructor-led walkthrough)
```
