# Desktop Todo Constitution

## Core Principles

### I. In-Memory Only
All task data stored in memory during runtime. No database, no file persistence. Data is ephemeral and resets on application restart.

### II. Single Module Architecture
Entire application contained in a single Python module (`todo.py`). No external dependencies beyond Python standard library for core functionality.

### III. Dataclass-Driven Models
All data models implemented as Python dataclasses. Immutable where possible, with clear field definitions and type hints.

### IV. CLI-First Interface
Primary interface is a console menu system. Users interact via numbered options. All output formatted for terminal display.

### V. Input Validation
All user input validated before processing. Empty inputs rejected. Invalid IDs handled gracefully with clear error messages.

### VI. Simplicity Over Features
YAGNI principles enforced. No premature abstractions. Features added only when explicitly required by specification.

## Constraints

- Python 3.10+ required
- No external database dependencies
- No file I/O for data persistence
- Console-only interface (no GUI, no web)
- Generated via Claude Code (no manual coding)

## Development Workflow

1. Specification defined in `.specify/` documents
2. Plan created before implementation
3. Implementation follows spec exactly
4. Changes require spec update first

## Governance

Constitution defines project boundaries. All features must align with core principles. Amendments require explicit user approval.

**Version**: 1.0.0 | **Ratified**: 2026-01-21 | **Last Amended**: 2026-01-21
