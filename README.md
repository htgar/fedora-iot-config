# Process
1) Set up `ansible-pull` with timer
2) Set up Tailscale with SSH using an authkey from secrets file, with forced reauth as systemd service
3) Seal the system to only allow access through tailscale
4) Install cockpit and associated extensions
5) Set up auto updates for rpm-ostree and podman

# References
<https://blog.while-true-do.io/iot-fedora-ansible-podman>
<https://blog.aleksic.dev/using-ansible-and-nomad-for-a-homelab-part-1>
