# CP2K docker container builds

## Why

CP2K is working on the container image for production, this repo attemps to port
the build scripts to also work on (slightly) older versions.

## Usage

Build the singularity image:

```bash
singularity build cp2k-v81-psmp.sif docker:yqshao/cp2k-docker:v8.1.0-psmp
```

Running the singularity image

```bash
mpirun cp2k-v81-psmp.sif -i input.inp
```

## Available versions

- v8.1.0-psmp
- v9.1.0-psmp
