# dh-systemd shim

This is a shim to provide `dh-systemd` to OS lacking it. Currently,
this mostly covers Ubuntu Precise. The shim is a noop. Its only use is
to be able to backport dh-systemd-enabled package without any change.
