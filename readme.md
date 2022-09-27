# Motorized axis Module

The Motorized axis module takes care of moves of one arm in angular mode with EMERSON driver. This module is written in SCL language and intended to be imported in Siemens TIA Portal and target S7-1500 PLC familly.

- TIA Portal version : V16, V17

## Repository governance

### Commit messages

- Use `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test` or `chore` as keywords type

- Use the following template `<type> <scope module> : <description>`

### Workflow

- Two main branches : `master` and `develop`

- Features branches are welcome : `feature/myfeature`

- All commits on `master` need to be tagged

### Tags description

- Tags need to follow the syntax `vX.Y.Z`

- `X` is the major revision tag : this needs to be incremented when external interfaces of Motorized axis module change

- `Y` is the minor revision tag : this needs to be incremented when additional internal features appear without changing external interfaces

- 'Z' is the bugfix revision tag : this needs to be incremented when the code changes without changing features or external interfaces


