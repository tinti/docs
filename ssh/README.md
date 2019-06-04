# Multiplexing

Add to `~/.ssh/config`.

```console
Host *
ControlPath ~/.ssh/master%r@%h:%p
ControlMaster auto
```
