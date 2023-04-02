# Zero Day — Development Environment Setup

> Configuring a reproducible Ubuntu development environment with Vagrant for the ALX Software Engineering program.

## Overview

Before writing any code in the ALX curriculum, a consistent Linux environment is required. This module covers **Day Zero** setup: provisioning an Ubuntu virtual machine using Vagrant so that every project compiles and runs the same way regardless of your host operating system.

A standard environment matches the ALX checker used for grading.

## Skills covered


- Linux virtual machine provisioning using Vagrant and VirtualBox (or another provider)
- Ubuntu environment verification for ALX development
- Understanding why a VM-based workflow is used in professional and educational settings
- SSH access to a remote/virtual machine and command execution in a Linux shell

## Tech Stack

| Tool | Purpose |
|---|---|
| Vagrant | VM provisioning and lifecycle management |
| VirtualBox | Hypervisor for the Ubuntu guest VM |
| Ubuntu 14.04/16.04 LTS | Target Linux environment |
| Bash | Shell inside the provisioned VM |

## Project Structure

| Module | Topic | What Was Practiced |
|---|---|---|
| `0x00-vagrant` | Environment setup | Vagrant VM provisioning, Ubuntu verification |

### Key files in `0x00-vagrant`

| File | Description |
|---|---|
| `0-hello_ubuntu` | Script or command output confirming the Ubuntu VM is running and accessible |
| `README.md` | Task documentation for the Vagrant setup exercise |

## Getting Started

```bash
git clone https://github.com/mgn-dev/zero_day.git
cd zero_day/0x00-vagrant

# From the directory containing your Vagrantfile:
vagrant up
vagrant ssh

# Inside the VM, verify the environment:
cat 0-hello_ubuntu
```

**Requirements:** Vagrant, VirtualBox (or compatible provider), Git.

## Curriculum Context

This is the **environment foundation** — everything else in the ALX program assumes this Ubuntu setup is in place.

| Previous | Next |
|---|---|
| — | [alx-pre_course](https://github.com/mgn-dev/alx-pre_course) — first Git and Bash tasks |
| — | [alx-zero_day](https://github.com/mgn-dev/alx-zero_day) — Git workflow deepening |
