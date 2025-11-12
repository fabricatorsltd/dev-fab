# fabricators Dev Kit

Containerfile for building the fabricators Development Kit Image.

## Build

You need the [Vib](https://github.com/vanilla-os/Vib) tool to generate the Containerfile.

```bash
vib build recipe.yml
podman image build -t fabricators/devkit .
```
