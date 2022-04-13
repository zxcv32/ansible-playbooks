Setup Kubernetes cluster on bare metal

OS
- orchestrator: Ubuntu 20.04
- node1: Ubuntu 20.04
- note2: Ubuntu 20.04

Versions
- Kubernetes: 1.23.5
- CRI-O: 1.23

Notes to self
- Check latest kubernetes version from PPA and update CRI-O version in env
- Setup static DHCP mapping for VMs
- Make sure DHCP pool don't overlap `172.21.250.0-172.21.255.254`
- Add DNS record to map domain name to IP address
- Setup password-less sudo
