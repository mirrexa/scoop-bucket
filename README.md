# Swarmfile Scoop bucket

Windows manifests for the standalone Swarmfile tools. Each manifest points at
the public release archive for the same version and pins its SHA-256.

```powershell
scoop bucket add mirrexa https://github.com/mirrexa/scoop-bucket
scoop install swarmfile-migrate
scoop install swarmfile-git-remote
scoop install swarmfile-doctor
```

`swarmfile-git-remote` installs `git-remote-swarmfile.exe`; git invokes it for
`swarmfile://` remotes. The tools are dual MIT/Apache-2.0.
