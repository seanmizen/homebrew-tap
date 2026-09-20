# seanmizen/homebrew-tap

Homebrew formulae for my tools.

```bash
brew install seanmizen/tap/shist
```

Or tap first, then install by name:

```bash
brew tap seanmizen/tap
brew install shist
```

## Formulae

| Formula | Description |
| --- | --- |
| [shist](https://github.com/seanmizen/shist) | Sean's History Tool (a shell history tool) |

## Maintenance

`Formula/shist.rb` is generated, not hand-edited. The `update formula` workflow
runs daily, reads the latest [shist release](https://github.com/seanmizen/shist/releases),
and commits the new version and checksums. To pull a release in immediately:

```bash
gh workflow run "update formula" -R seanmizen/homebrew-tap
```

Pass a tag to pin a specific version:

```bash
gh workflow run "update formula" -R seanmizen/homebrew-tap -f tag=v1.0.1
```
