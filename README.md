<div align="center">
<h1>🍌 Banan 🍌</h1>
<p>Banan Inc (fake company) organization monolithic repository</p>
<a href="https://gitpod.io/#https://github.com/how-do-you/banan"><img src="https://img.shields.io/badge/gitpod.io-launch-blue"></a>
</div>

## Getting started

You can either clone the repository to your own computer and edit it in your favorite IDE, or you can launch it in
Gitpod, your second most favorite IDE.

```shell
# Build all crates
cargo build
# Install frontend dependencies
cd crates/com-banan-frontend
yarn
# Launch Tauri
cd crates/com-banan-tauri
cargo tauri dev
```

If you're on Gitpod, open the service on port `6080` to view the app. You can find the services in the menu on the left in
Gitpod. Note that by default when you launch in Gitpod it will immediately start building both the frontend and the
tauri crates, hence the long wait time at the start. Be patient!

Hot reload works as intended, put the NoVNC window on one monitor, and the IDE on the other, make a change in the source
files, both Tauri and Nuxt will automatically detect it and reload.
