# Verification plan — Windows laptops

Status: NOT RUN. There is no executable implementation to test.

## Module acceptance criteria

### 1. Battery report import

- [ ] Define a versioned input fixture specifically for battery report import.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

### 2. Capacity trend chart

- [ ] Define a versioned input fixture specifically for capacity trend chart.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

### 3. Workload context annotations

- [ ] Define a versioned input fixture specifically for workload context annotations.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

## Release gate

- [ ] Implement the proposed modules and add automated tests.
- [ ] Record exact tested versions; leave untested versions marked unknown.
- [ ] Verify backups and restoration where state changes are supported.
- [ ] Review privacy, permissions, and product rules.
- [ ] Publish source and reproducible build instructions before claiming a working release.
- [ ] Do not present the retained external resource as a verified download.

## Scope

Observe and report first; any later change requires separate confirmation. Do not disable antivirus, updates, or other protections. No automatic data deletion or guaranteed performance gains. Do not collect passwords, tokens, or private file contents.
