# Upgrade

1. Bump version in PKGBUILD
2. Run `updpkgsums`
3. Run `makepkg --printsrcinfo > .SRCINFO`
4. Test with `makepkg -si`
