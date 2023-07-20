# RsaCtfTool Docker Image

Based on: https://github.com/callrbx/rsactftool-docker

My Changes:
- Changed `ENTRYPOINT` by `CMD` so you can work inside the shell's container
- Added `/data` directory and made it the `WORKDIR`, to mount a directory

---

Simple a Docker build for the latest RSACTFTool

This is an updated image for more recent releases that use python3.

Includes sagemath.

I did no work on the underlying tool, that is all Ganapati's great work!

Build locally:
```
docker build -t jforcada/rsactftool:local .
```

Run with:
```
docker run jforcada/rsactftool <tool options>
```

[RsaCtfTool](https://github.com/Ganapati/RsaCtfTool)
