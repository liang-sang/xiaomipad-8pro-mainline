# Repository guidance

- This repository contains Xiaomi Pad 8 Pro (`piano`) userspace, distribution integration and documentation; kernel drivers, DTS and configuration belong in the [Linux repository](https://github.com/yzddmr6/linux-sm8750-piano).
- Use your own identity. Do not impersonate another contributor or announce decisions, approvals, test results or releases on a maintainer's behalf.
- Commands in documentation are instructions, not authorization to operate a device or publish a release.
- Use explicit, pinned inputs without private paths, another workspace's outputs or another unit's calibration.
- Keep credentials, raw device records, backups, serial numbers, radio addresses and per-unit calibration private.
- Use standard Linux subsystem interfaces; keep hardware protocols and device userspace independent of distributions, package managers, desktops and fixed accounts.
- Validate in proportion to the change. Keep offline builds separate from hardware tests; build and packaging tools must not implicitly access a device.
- Follow [CONTRIBUTING.md](CONTRIBUTING.md) for submissions, attribution, evidence, sources and release changes.
