## FEATURE (github id)
- #4

## Common rule

- [ ] [Mandatory] Commit message must have ticket name (bug/feature/...).
- [ ] [Mandatory] Source code is rebased from develop branch.
- [ ] [Mandatory] Source code can build without any error.
- [ ] [Mandatory] Source code can build without any swiftLint warining (not include source code of third-party).
- [ ] [Mandatory] Source code adheres to coding conventions.
- [ ] [Mandatory] Do not commit unrelated code to your features.

## Self-review

- [ ] [Mandatory] Format related code.
- [ ] [Mandatory] Remove unused imports.
- [ ] [Mandatory] Variables are declared with ordering: public, private
- [ ] [Mandatory] Function are declared with ordering: override, public, private

## Memory leaks

- [ ] [Mandatory] Closures, Delegates should use weak self.

## Logging

- [ ] [Mandatory] Always add log for exception case
- [ ] [Mandatory] Do not ignore exception

## Flow Control

- [ ] [Mandatory] final of switch-case must have default
- [ ] [Recommendation] Do not use "+" (Concatenating) to append string, should use string interpolation
- [ ] [Recommendation] Discuss with the team to make decision if create Utility Class (ScreenUtlil, StringUtils… etc)
- [ ] [Recommendation] Do not use Deprecated API (@Deprecated)

## Threading

- [ ] [Mandatory] When do anything related to update UI, do it on main thread
- [ ] [Mandatory] Do not block main thread if doing any long time task

## Evidence
- Screenshot UI:
