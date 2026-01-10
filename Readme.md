# 🐧 Linux Basics – Introduction

This document introduces the fundamentals of Linux, including:
- What an Operating System is
- What Linux is
- Linux kernel and system structure
- Linux distributions
- Package managers

---

## 📌 What is an Operating System (OS)?

An **Operating System (OS)** is system software that:
- Manages hardware resources (CPU, memory, storage, network)
- Provides services for applications
- Acts as an interface between **hardware and user applications**

Without an OS, users and applications cannot efficiently interact with hardware.

---

## 📌 What is Linux?

**Linux** is an open-source, Unix-like **operating system kernel** developed by **Linus Torvalds in 1991**.

Linux is widely used in:
- Servers
- Cloud environments
- Embedded systems
- Desktop operating systems

> Technically, Linux refers to the **kernel**, while a Linux OS includes the kernel plus tools and utilities.

---

## 📌 Linux Kernel

The **Linux kernel** is the core component of the operating system.

### Responsibilities of the Kernel:
- Process management
- Memory management
- Device drivers
- Networking
- File system handling

The kernel runs in **privileged mode** and directly communicates with hardware.

---

## 📌 Linux System Structure

Linux follows a **layered architecture**:

+-------------------------+
| Applications |
+-------------------------+
| Shell (CLI) |
+-------------------------+
| System Libraries |
+-------------------------+
| Linux Kernel |
+-------------------------+
| Hardware |
+-------------------------+


### Layer Description:
- **Applications**: User programs (editors, browsers, servers)
- **Shell**: Command-line interface (bash, zsh)
- **System Libraries**: APIs that allow applications to interact with the kernel
- **Kernel**: Core OS component
- **Hardware**: Physical resources (CPU, RAM, Disk, Network)

---

## 📌 Linux Distributions

A **Linux distribution (distro)** is a complete operating system built around the Linux kernel and includes:
- Package manager
- System utilities
- Desktop environment (optional)

### Popular Linux Distributions:
- Ubuntu (Debian-based)
- Debian
- CentOS / Rocky Linux (RHEL-based)
- Fedora
- Arch Linux

---

## 📌 Package Managers

A **package manager** helps install, update, and remove software packages on Linux systems.

### Common Package Managers:

| Distro Family     | Package Manager |
|------------------|----------------|
| Debian / Ubuntu  | `apt`          |
| RHEL / CentOS    | `yum` / `dnf`  |
| Arch Linux       | `pacman`       |

---

### 📦 Package Manager Examples

#### Debian / Ubuntu
```bash
sudo apt update
sudo apt install nginx

RHEL sudo yum install nginx
ARCH Linux sudo pacman -S nginx
