# Sonetto-Patch

### How to use
Download latest build from [releases page](https://github.com/yoncodes/sonetto-patch/releases) and extract contents of it into the game folder<br>
Run `launcher.exe` (**AS ADMINISTRATOR**)

### Want to compile it yourself?
- Clone the repo
- Install rustup
- Run `cargo build --release`

### What does it patch, actually?
- Redirects game's network requests to `127.0.0.1:21000`, so you don't need to use proxy
