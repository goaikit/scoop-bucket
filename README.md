# Scoop Bucket for AIKIT

Install [aikit](https://github.com/goaikit/aikit) via Scoop on Windows.

## Installation

### Option 1: Add Bucket (Recommended)

This method enables automatic updates via `scoop update`:

```powershell
scoop bucket add gofastskill https://github.com/goaikit/scoop-bucket
scoop install aikit
```

### Option 2: Direct Install (Single Line)

Install directly from the manifest URL without adding a bucket:

```powershell
scoop install https://raw.githubusercontent.com/goaikit/scoop-bucket/main/bucket/aikit.json
```

Note: This method does not track updates automatically.

## Usage

```powershell
aikit --version
```

## Upgrading

```powershell
scoop update aikit
```

## Uninstalling

```powershell
scoop uninstall aikit
scoop bucket rm goaikit
```

## Learn More

- [FastSkill GitHub](https://github.com/goaikit)

