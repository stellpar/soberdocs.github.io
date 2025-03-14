# Tested Linux Distros + Versions

---

> Please feel free to contribute to this table via. Pull Requests with any valid results.

## Point release distros
### Debian
| Tested version | Test date | Test authored by                              | Test method                    | Installs? | Runs? | Notes |
| -------------- | --------- | --------------------------------------------- | ------------------------------ | --------- | ----- | ----- |
| 11             | 10/18/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1      | Yes       | No    | Able to pass GPG verification and installs, but does not launch without logs, even with OpenGL invoked |
| 12             | 10/18/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1      | Yes       | Yes   |       |

### Ubuntu
> Ubuntu has multiple flavours based on the base desktop environment installed out of the box. Regardless, they are to be treated as one.

| Tested version | Test date | Test authored by                              | Test method                    | Installs? | Runs? | Notes |
| -------------- | --------- | --------------------------------------------- | ------------------------------ | --------- | ----- | ----- |
| 20.04 LTS      | 10/18/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1      | Yes       | No    | Mesa too old to attach to X11, libEGL too old to know if screen is DRI3 capable; despite able to run barebones, unable to install (and therefore run) Roblox under these conditions |
| 22.04 LTS      | 10/18/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1      | Yes       | Yes   |       |

### Fedora Linux
> Like Ubuntu, Fedora has other versions based on the base desktop environment installed out of the box. Likewise, they are to be treated as one regardless.

| Tested version | Test date | Test authored by                              | Test method                    | Installs? | Runs? | Notes |
| -------------- | --------- | --------------------------------------------- | ------------------------------ | --------- | ----- | ----- |
| 39             | 10/18/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1      | Yes       | Yes   | EOL version |
| 40             | 10/18/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | Phyiscal machine               | Yes       | Yes   |       |
| 41             | 11/01/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | Phyiscal machine               | Yes       | Yes   |       |

### openSUSE (Leap)
| Tested version | Test date | Test authored by                              | Test method            | Installs? | Runs? | Notes |
| -------------- | --------- | --------------------------------------------- | ---------------------- | --------- | ----- | ----- |
| TBA            | TBA       |                                               |                        | TBA       | TBA   |       |

---

## Rolling release distros
> Rolling release distros usually don't have a point release version. For this, it will be tested peridotically. On the table, the test date is the most contextical.

> There is currently an issue in Arch distros (especially if it's a fresh install) where attempting to install NVIDIA 565 Flatpak drivers in user mode (`--user`) will result in a Segmentation Fault error. The current only workaround is to install Sober on system level (without `--user`)

### Arch Linux
| Test date | Test authored by                              | Test method               | Installs? | Runs? | Notes |
| --------- | --------------------------------------------- | ------------------------- | --------- | ----- | ----- |
| 11/08/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1 | Yes       | Yes   |       |

### EndeavourOS
| Test date | Test authored by                              | Test method               | Installs? | Runs? | Notes |
| --------- | --------------------------------------------- | ------------------------- | --------- | ----- | ----- |
| 11/08/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1 | Yes       | Yes   |       |
| 01/14/25  | [kirbix (k1yrix)](https://github.com/k1yrix)  | Physical Machine          | Yes       | Yes   |       |

### Manjaro
| Test date | Test authored by                              | Test method               | Installs? | Runs? | Notes |
| --------- | --------------------------------------------- | ------------------------- | --------- | ----- | ----- |
| 11/08/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1 | Yes       | Inconclusive | For some reason, Manjaro faced the relevant issue when Ubuntu 20.04 LTS was tested. I have no idea what is going on with Mesa nor I have no idea who's fault is it that causes this issue, despite it should be an up-to-date version/system. Will require further testing. |

### openSUSE (Tumbleweed)
| Test date | Test authored by                              | Test method               | Installs? | Runs? | Notes |
| --------- | --------------------------------------------- | ------------------------- | --------- | ----- | ----- |
| 11/08/24  | [kirbix (k1yrix)](https://github.com/k1yrix)  | VMware Workstation 17.6.1 | Yes       | Yes   |       |
