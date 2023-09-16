## Tools to help reproducible builds of container images

- <https://github.com/reproducible-containers/repro-sources-list.sh>: best for Debian, Ubuntu, ArchLinux
- <https://github.com/reproducible-containers/repro-pkg-cache>: best for Alpine, Fedora, Rocky, openSUSE, etc.

See also: <https://github.com/moby/buildkit/blob/master/docs/build-repro.md>

## Tools to analyze unreproducible container images
- <https://github.com/reproducible-containers/diffoci>: diff for Docker and OCI (Open Container Initiative) container images

## Misc
- <https://github.com/reproducible-containers/buildkit-cache-dance>: Save `--mount=type=cache` caches on GitHub Actions (to reduce loads on `snapshot.debian.org` etc.)
- <https://github.com/reproducible-containers/buildkit-nix>: Nix as Dockerfiles (`docker build -f default.nix .`)
- <https://github.com/reproducible-containers/repro-get>: [Soft-deprecated] Reproducible apt/dnf/apk/pacman, with content-addressing
