⚡ SKILSTAK Quick Start Container Image

Start learning Linux and containers now. Whether you are coming into the Boost late and want to catch up to keep up with live streams or you just want to get Linux on your local computer as fast as possible here is the fastest way to get started.

<https://youtu.be/Nfq26YHssj8>

1. Install terminal software
   * Mac: iTerm2
   * Windows: Terminal Preview
1. Install bash
   * Mac: install brew (then) brew install bash
   * Windows: install git-bash
1. Install Podman Desktop
1. Initialize and start the podman virtual machine
   * Open bash terminal command line
   * `podman machine list`
   * `podman machine init`
   * `podman machine start`
1. Create a container from SKILSTAK workspace image
   * `podman run -it --hostname skilstak --name skilstak -v shared://shared ghcr.io/rwxrob/ws-skilstak`
   * Use exit to exit container
   * `podman start -a skilstak`
