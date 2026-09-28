# libudev

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/l/libudev.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/libudev1-257.4-hbe16f8c_1.conda | `56e55a7e7380a980b418c282cb0240b3ac55ab9308800823ff031a9529e2f013` | conda-forge libudev1 257.4 hbe16f8c_1 (LGPL-2.1-or-later) |

## Command

```
.agents/tools/repack/repack.py \
    --name libudev \
    --version 257.4 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/libudev1-257.4-hbe16f8c_1.conda#56e55a7e7380a980b418c282cb0240b3ac55ab9308800823ff031a9529e2f013 \
    --host 'lib/libudev.so*' \
    --require lib/libudev.so.1
```

