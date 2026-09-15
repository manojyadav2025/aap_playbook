# Ansible Role: rhel_mounts

An Ansible role that automatically discovers safe, unpartitioned raw disks (bypassing root and ASM signatures), pools them into an LVM Volume Group, creates multiple Logical Volumes, formats them (`xfs`), and configures persistent mounts in `/etc/fstab`.
