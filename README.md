# Salome Meca - flatpak
> Warning
> Not working yet
## Prerequisites
Just make sure that the required Sdk and the Platform are installed:
```
flatpak install flathub org.freedesktop.Sdk
flatpak install flathub org.freedesktop.Platform
```
## Building
Just:
```
flatpak-builder --force-clean --repo=repo salome_meca org.freedesktop.SalomeMeca.json
```
