# ffmpeg-builds

Static FFmpeg binaries repackaged for the AG hosting fleet (32-bit i686 servers, glibc 2.8).

## ffmpeg-7.0.2-i686-static.tar.gz

- Source: johnvansickle.com FFmpeg static builds (`ffmpeg-release-i686-static`, FFmpeg 7.0.2)
- Repackaged as tar.gz (server extractable with `tar` + `gzip`; the originals are tar.xz which the old servers cannot unpack).
- Contents: `ffmpeg`, `ffprobe`, `LICENSE.txt`

### Checksums (SHA-256)

| File | SHA-256 |
|---|---|
| `ffmpeg` | `c6472eb993612db72ca50893a34137ba11173e60a1a4c028d4660a3f755d2490` |
| `ffprobe` | `a13b4cce0a4b9bd6714672e4df81076ec06f4c295d798162d48e3de68c781d6d` |
| `LICENSE.txt` | `8ceb4b9ee5adedde47b31e975c1d90c73ad27b6b165a1dcd80c7c545eb65b903` |
| `ffmpeg-7.0.2-i686-static.tar.gz` | `565c63dbd1986b90b71ce4570322b3a3b67337f6a55fa01c95ab05d693c1f47a` |
