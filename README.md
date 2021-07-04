# HarfBuzz

This is **HarfBuzz**, a text shaping library.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/harfbuzz
$ dnf install -y harfbuzz
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y harfbuzz
```

## Remove

```
$ dnf erase -y harfbuzz
$ dnf copr remove pkgstore/harfbuzz
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/harfbuzz).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/harfbuzz) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
